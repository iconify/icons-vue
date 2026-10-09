<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgrtu-b6i.css';
import '../../css/l/ldszce0qy.css';
import '../../css/q/q5jodccjc.css';
import '../../css/h/huyo77usb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qgrtu-b6i"/><path class="ldszce0qy"/><path class="q5jodccjc"/><path class="huyo77usb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:community-energy-48" /></template>
