<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewio2v6iy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ewio2v6iy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:hair-cross" /></template>
