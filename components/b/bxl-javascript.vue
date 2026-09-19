<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0s1z4bba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q0s1z4bba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-javascript" /></template>
