<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffw97mbwu.css';
import '../../css/z/z15e8vbuh.css';
import '../../css/p/p9ipl3bri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ffw97mbwu"/><rect class="z15e8vbuh"/><path class="p9ipl3bri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:hardware-chip" /></template>
