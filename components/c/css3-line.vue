<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzd1uqbmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hzd1uqbmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:css3-line" /></template>
