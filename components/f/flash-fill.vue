<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzzpmz_bo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzzpmz_bo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flash-fill" /></template>
