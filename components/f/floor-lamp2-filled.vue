<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhiy3obdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhiy3obdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:floor-lamp2-filled" /></template>
