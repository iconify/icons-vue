<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zidxgwc3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="zidxgwc3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:arrow-left-stroke-12" /></template>
