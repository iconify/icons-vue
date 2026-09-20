<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_2newb8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":24};
const content = `<path class="i_2newb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:arrow-left-long-expressive" /></template>
