<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvy1d59je.css';
import '../../css/l/lidjc4bcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvy1d59je"/><path class="lidjc4bcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:clock-dashed-half" /></template>
