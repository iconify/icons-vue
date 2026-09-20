<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um71q_bhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="um71q_bhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:cut" /></template>
