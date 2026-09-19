<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/by9j8n7zb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="by9j8n7zb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:air-balloon" /></template>
