<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2f20nb-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="n2f20nb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:cube-transparent-16-solid" /></template>
