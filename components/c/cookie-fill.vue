<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axsiesbbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="axsiesbbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cookie-fill" /></template>
