<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex-auqnvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ex-auqnvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:gallery-vertical-end-line" /></template>
