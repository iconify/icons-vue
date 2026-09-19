<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hq6_tcb-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hq6_tcb-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:boar-ensign" /></template>
