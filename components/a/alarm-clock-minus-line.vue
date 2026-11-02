<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcfax0boh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hcfax0boh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:alarm-clock-minus-line" /></template>
