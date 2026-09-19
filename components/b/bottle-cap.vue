<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4wl_ub8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s4wl_ub8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bottle-cap" /></template>
