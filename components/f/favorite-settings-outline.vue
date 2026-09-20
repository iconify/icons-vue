<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmpc50jny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmpc50jny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:favorite-settings-outline" /></template>
