<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hc4m7k-7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hc4m7k-7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:bank" /></template>
