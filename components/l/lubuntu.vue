<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9y1vebjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9y1vebjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:lubuntu" /></template>
