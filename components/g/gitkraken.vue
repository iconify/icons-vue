<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfiie8bwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yfiie8bwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:gitkraken" /></template>
