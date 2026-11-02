<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oro_tfbhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oro_tfbhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chevrons-left-right-line" /></template>
