<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl2dx3bze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vl2dx3bze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:login-half-circle-line" /></template>
