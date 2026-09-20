<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0mw04lqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i0mw04lqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:appearance" /></template>
