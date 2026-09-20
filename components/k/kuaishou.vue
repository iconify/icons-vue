<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhzv1zwvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhzv1zwvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:kuaishou" /></template>
