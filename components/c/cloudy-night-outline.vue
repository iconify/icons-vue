<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4ylmckef.css';
import '../../css/h/htohhkvke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f4ylmckef"/><path class="htohhkvke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:cloudy-night-outline" /></template>
