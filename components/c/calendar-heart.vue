<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcm9zqbhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hcm9zqbhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:calendar-heart" /></template>
