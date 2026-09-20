<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlkhq1c-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hlkhq1c-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:eraser-off" /></template>
