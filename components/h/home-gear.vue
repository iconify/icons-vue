<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_x43ob0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_x43ob0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:home-gear" /></template>
