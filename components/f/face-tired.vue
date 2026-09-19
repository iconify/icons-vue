<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0espduqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y0espduqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:face-tired" /></template>
