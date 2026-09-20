<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqqf0usjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mqqf0usjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chandelier-filled" /></template>
