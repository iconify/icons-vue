<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkc2bcb8o.css';
import '../../css/o/oevl03-th.css';
import '../../css/t/tv3azrqgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pkc2bcb8o"/><path class="oevl03-th"/><path class="tv3azrqgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-restaurant" /></template>
