<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tswgzy9an.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tswgzy9an"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bear-spray-can-with-spray-and-dollar" /></template>
