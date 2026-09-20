<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km7s_km6t.css';
import '../../css/n/nb04b04xe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="km7s_km6t"/><path class="nb04b04xe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:e-commerce-apparel-bold" /></template>
