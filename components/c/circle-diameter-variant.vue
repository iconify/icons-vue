<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n280i_but.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n280i_but"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:circle-diameter-variant" /></template>
