<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sw_wutbxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sw_wutbxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:chevron-up-stroke-16" /></template>
