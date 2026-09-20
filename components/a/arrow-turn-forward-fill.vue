<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikp3ozb_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikp3ozb_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-turn-forward-fill" /></template>
