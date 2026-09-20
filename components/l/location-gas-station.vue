<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzj13qb9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rzj13qb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:location-gas-station" /></template>
