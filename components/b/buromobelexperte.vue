<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nw1ycublj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nw1ycublj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:buromobelexperte" /></template>
