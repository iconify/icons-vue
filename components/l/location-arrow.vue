<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2-g-ztup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="w2-g-ztup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:location-arrow" /></template>
