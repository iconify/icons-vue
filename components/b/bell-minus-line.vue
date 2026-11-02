<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhikcmbin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hhikcmbin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bell-minus-line" /></template>
