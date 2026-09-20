<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1i_g2pvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1i_g2pvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:contentful" /></template>
