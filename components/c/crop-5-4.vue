<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-w1iwbwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-w1iwbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:crop-5-4" /></template>
