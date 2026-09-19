<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz30bjbrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oz30bjbrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ceiling-buratto-four" /></template>
