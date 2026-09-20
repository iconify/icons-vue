<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj9bjxbme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hj9bjxbme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:deepinfra" /></template>
