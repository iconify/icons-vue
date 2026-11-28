<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udlxi0b4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udlxi0b4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:drone" /></template>
