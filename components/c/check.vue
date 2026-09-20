<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmlji-8lx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmlji-8lx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:check" /></template>
