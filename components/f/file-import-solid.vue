<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skjtd3mxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="skjtd3mxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:file-import-solid" /></template>
