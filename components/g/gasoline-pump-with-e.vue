<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfvy7ybmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jfvy7ybmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:gasoline-pump-with-e" /></template>
