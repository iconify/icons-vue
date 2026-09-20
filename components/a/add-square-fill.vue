<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kso4zxb6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kso4zxb6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:add-square-fill" /></template>
