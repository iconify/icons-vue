<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyib19brx.css';
import '../../css/z/z477j3bdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eyib19brx"/><rect class="z477j3bdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:archive" /></template>
