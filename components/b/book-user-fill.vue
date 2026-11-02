<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgbvr3_yh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xgbvr3_yh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-user-fill" /></template>
