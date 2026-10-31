<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzfrzlhey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fzfrzlhey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bus-fill-round" /></template>
