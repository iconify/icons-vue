<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocurxub7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ocurxub7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:flip-horizontal-2-fill" /></template>
