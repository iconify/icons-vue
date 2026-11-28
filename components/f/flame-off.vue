<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1bb8rb3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1bb8rb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:flame-off" /></template>
