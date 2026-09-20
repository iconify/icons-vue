<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up2z56_ho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="up2z56_ho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:cratedb" /></template>
