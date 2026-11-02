<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs3lceb3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gs3lceb3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:citrus-fill" /></template>
