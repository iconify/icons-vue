<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj84-dzad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hj84-dzad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:location-arrow" /></template>
