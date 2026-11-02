<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1i-prnbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1i-prnbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flower-4-fill" /></template>
