<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mz09tfcia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mz09tfcia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-rainy" /></template>
