<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mz01nob5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mz01nob5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:audi-alt" /></template>
