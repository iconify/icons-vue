<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz1q1stlw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fz1q1stlw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cloud-rain-filled" /></template>
