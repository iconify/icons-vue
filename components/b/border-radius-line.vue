<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kr30rzbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kr30rzbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:border-radius-line" /></template>
