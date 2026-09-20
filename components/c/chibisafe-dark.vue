<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/teznrsbms.css';
import '../../css/y/ypvg3cc4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="teznrsbms"/><path class="ypvg3cc4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:chibisafe-dark" /></template>
