<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucujz0b4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ucujz0b4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:checkmark" /></template>
