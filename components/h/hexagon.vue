<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4yh9sqql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4yh9sqql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:hexagon" /></template>
