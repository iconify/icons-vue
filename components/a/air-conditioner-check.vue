<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l09febj2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l09febj2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:air-conditioner-check" /></template>
