<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfjdz5bhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mfjdz5bhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:hotel-star" /></template>
