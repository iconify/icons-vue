<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5n2jta6r.css';
import '../../css/t/t8fe1nbtx.css';
import '../../css/e/eg1wrabcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d5n2jta6r"/><path class="t8fe1nbtx"/><path class="eg1wrabcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:compressor-20" /></template>
