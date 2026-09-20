<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2h51-bjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2h51-bjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:dotenv" /></template>
