<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgb91bumo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgb91bumo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-to-top-stroke" /></template>
