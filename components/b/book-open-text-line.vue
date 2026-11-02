<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pardkfbho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pardkfbho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-open-text-line" /></template>
