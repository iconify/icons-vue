<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytet-by2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ytet-by2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kibana-dark" /></template>
