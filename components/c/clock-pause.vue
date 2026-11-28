<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cny6ftb5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cny6ftb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:clock-pause" /></template>
