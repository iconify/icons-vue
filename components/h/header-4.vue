<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i16_tg4yp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="i16_tg4yp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:header-4" /></template>
