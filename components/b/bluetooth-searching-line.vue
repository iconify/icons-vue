<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvsj64bfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvsj64bfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bluetooth-searching-line" /></template>
