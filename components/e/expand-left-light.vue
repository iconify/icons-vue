<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjwj45jme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjwj45jme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:expand-left-light" /></template>
