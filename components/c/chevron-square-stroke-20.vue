<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kun0b6tvp.css';
import '../../css/f/fppjkf2zl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kun0b6tvp"/><path class="fppjkf2zl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:chevron-square-stroke-20" /></template>
