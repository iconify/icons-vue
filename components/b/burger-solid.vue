<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8atly0_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="i8atly0_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:burger-solid" /></template>
