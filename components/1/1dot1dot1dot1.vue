<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-4vy0bvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-4vy0bvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:1dot1dot1dot1" /></template>
