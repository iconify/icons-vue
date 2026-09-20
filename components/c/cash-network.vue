<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hivfxibsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hivfxibsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:cash-network" /></template>
