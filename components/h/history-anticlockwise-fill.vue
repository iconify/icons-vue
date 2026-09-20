<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/libgasujb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="libgasujb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:history-anticlockwise-fill" /></template>
