<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exh-jfbmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="exh-jfbmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:book-compact" /></template>
