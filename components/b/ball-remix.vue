<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jiyu1gbpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jiyu1gbpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:ball-remix" /></template>
