<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i66pb1b_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i66pb1b_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:attachment" /></template>
