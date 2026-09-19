<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jso90vbkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jso90vbkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:editor-indent" /></template>
