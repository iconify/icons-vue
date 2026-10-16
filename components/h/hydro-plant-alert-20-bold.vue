<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p16fzd8jz.css';
import '../../css/r/rpdwkt9nl.css';
import '../../css/j/jeyqzjnhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p16fzd8jz"/><path class="rpdwkt9nl"/><path class="jeyqzjnhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydro-plant-alert-20-bold" /></template>
