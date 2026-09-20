<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zohpjsaqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zohpjsaqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ad-rectangle-off-fill" /></template>
