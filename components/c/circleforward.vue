<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2gi3tfwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="i2gi3tfwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:circleforward" /></template>
