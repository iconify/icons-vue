<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjikcm-3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jjikcm-3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:file-video" /></template>
