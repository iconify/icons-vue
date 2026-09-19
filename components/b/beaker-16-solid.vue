<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/devb-9bdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="devb-9bdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:beaker-16-solid" /></template>
