<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjlq3pbnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjlq3pbnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:circle-x" /></template>
