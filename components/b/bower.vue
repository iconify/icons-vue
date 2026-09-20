<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di13lq8_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="di13lq8_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bower" /></template>
