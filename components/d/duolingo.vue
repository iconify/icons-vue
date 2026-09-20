<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjum-4nsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjum-4nsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:duolingo" /></template>
