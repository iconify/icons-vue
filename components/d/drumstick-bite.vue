<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/am2xe984g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="am2xe984g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:drumstick-bite" /></template>
