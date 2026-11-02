<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ki14_kbiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ki14_kbiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:home-6-fill" /></template>
