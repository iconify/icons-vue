<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbk4c6bbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbk4c6bbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:freetube" /></template>
