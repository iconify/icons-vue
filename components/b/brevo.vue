<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yoxr4ab1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yoxr4ab1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:brevo" /></template>
