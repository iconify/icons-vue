<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ig_amlb1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ig_amlb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:bell-minus" /></template>
