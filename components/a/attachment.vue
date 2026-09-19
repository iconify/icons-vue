<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o93giq6ri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="o93giq6ri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:attachment" /></template>
