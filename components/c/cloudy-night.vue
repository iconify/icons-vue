<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kru6wy-1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kru6wy-1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:cloudy-night" /></template>
