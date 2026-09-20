<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7tkfmbai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7tkfmbai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:firework-fill" /></template>
