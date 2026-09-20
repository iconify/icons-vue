<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrh8mub3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nrh8mub3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bnb-fill" /></template>
