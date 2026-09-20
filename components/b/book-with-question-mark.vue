<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f12yfw9qr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f12yfw9qr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:book-with-question-mark" /></template>
