<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwflmfbjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":472};
const content = `<path class="qwflmfbjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:browser" /></template>
