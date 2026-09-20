<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyrqv0bac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vyrqv0bac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:adidas" /></template>
