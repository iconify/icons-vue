<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mie05o1hb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mie05o1hb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:dislike" /></template>
