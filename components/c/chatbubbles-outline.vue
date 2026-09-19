<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ri6_m1b9d.css';
import '../../css/v/v4jtutbyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ri6_m1b9d"/><path class="v4jtutbyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:chatbubbles-outline" /></template>
