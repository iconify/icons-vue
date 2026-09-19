<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oze8g3fll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="oze8g3fll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:file-circle-exclamation" /></template>
