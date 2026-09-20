<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5fnoe3le.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5fnoe3le"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:dice-3-line" /></template>
