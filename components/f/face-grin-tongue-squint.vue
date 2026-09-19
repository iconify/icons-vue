<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i47d-_nwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i47d-_nwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:face-grin-tongue-squint" /></template>
