<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4si8guta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":1792};
const content = `<path class="h4si8guta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:connectdevelop" /></template>
