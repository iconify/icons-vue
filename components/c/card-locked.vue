<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f86-l3b-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f86-l3b-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:card-locked" /></template>
