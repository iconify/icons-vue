<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2imh-b4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w2imh-b4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:chia-network" /></template>
