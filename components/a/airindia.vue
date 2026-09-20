<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/leyozg8sl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="leyozg8sl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:airindia" /></template>
