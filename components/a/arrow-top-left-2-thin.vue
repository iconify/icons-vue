<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu4uyrb_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fu4uyrb_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-top-left-2-thin" /></template>
