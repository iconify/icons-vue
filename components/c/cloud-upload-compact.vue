<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sd0mwet8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="sd0mwet8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:cloud-upload-compact" /></template>
