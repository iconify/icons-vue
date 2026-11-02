<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usqribf4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usqribf4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layers-minus-line" /></template>
