<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1gl-tqmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j1gl-tqmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:earth-lock-fill" /></template>
