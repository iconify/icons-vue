<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0v0ilbui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1792};
const content = `<path class="l0v0ilbui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:file-word-o" /></template>
