<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q31pl2bmr.css';
import '../../css/y/y0lh2dbky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q31pl2bmr"/><path class="y0lh2dbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-star-line" /></template>
