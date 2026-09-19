<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfmoecckr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfmoecckr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-c-plus-plus" /></template>
