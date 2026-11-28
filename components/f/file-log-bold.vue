<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmafribiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="dmafribiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:file-log-bold" /></template>
