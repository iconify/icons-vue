<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s--xkeuto.css';
import '../../css/j/j4u5ysbzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s--xkeuto"/><path class="j4u5ysbzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:charger-location-20-bold" /></template>
