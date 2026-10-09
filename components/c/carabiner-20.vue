<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwfalccns.css';
import '../../css/v/v4w_f_aee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rwfalccns"/><path class="v4w_f_aee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:carabiner-20" /></template>
