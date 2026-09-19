<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlzbi5xzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xlzbi5xzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:google" /></template>
