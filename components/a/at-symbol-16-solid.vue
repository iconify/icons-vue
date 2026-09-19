<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqedgs0ds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zqedgs0ds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:at-symbol-16-solid" /></template>
