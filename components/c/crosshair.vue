<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6a9ptc7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6a9ptc7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:crosshair" /></template>
