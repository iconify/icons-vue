<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb7he3brl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mb7he3brl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:bread-loaf-bold" /></template>
