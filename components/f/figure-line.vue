<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkth-jr_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qkth-jr_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:figure-line" /></template>
