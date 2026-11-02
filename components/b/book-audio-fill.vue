<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly5yssbjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ly5yssbjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-audio-fill" /></template>
