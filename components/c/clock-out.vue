<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-1--_lvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-1--_lvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clock-out" /></template>
