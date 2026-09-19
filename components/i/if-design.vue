<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5e_gbbhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i5e_gbbhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:if-design" /></template>
