<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svhbf3bmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svhbf3bmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fullscreen-exit-fill" /></template>
