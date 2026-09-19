<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4z-3_leu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1792};
const content = `<path class="q4z-3_leu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:file-pdf-o" /></template>
