<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rytk2ybhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rytk2ybhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:building-plus" /></template>
