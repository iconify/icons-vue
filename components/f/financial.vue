<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf7v85bwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="mf7v85bwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:financial" /></template>
