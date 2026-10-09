<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpeye7b8j.css';
import '../../css/t/trobavbbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fpeye7b8j"/><path class="trobavbbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:anemometer-20-bold" /></template>
