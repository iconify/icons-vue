<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_vll34og.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r_vll34og"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:application-screen-play" /></template>
