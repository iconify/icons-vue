<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w11ibabcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w11ibabcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:dumbbell2-filled" /></template>
