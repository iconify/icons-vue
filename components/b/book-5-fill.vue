<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjf9-p5gg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gjf9-p5gg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-5-fill" /></template>
