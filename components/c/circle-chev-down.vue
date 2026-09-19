<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0y2p2isn.css';
import '../../css/p/pr22v0bjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q0y2p2isn"/><path class="pr22v0bjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:circle-chev-down" /></template>
