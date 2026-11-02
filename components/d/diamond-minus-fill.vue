<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fq-33qbhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fq-33qbhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:diamond-minus-fill" /></template>
