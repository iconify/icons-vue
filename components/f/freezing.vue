<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn2gz5idw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="xn2gz5idw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:freezing" /></template>
