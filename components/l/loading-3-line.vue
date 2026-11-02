<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9cj9y50u.css';
import '../../css/o/oy6hf0bjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9cj9y50u"/><path class="oy6hf0bjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:loading-3-line" /></template>
