<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzb-k98lc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tzb-k98lc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:led-off" /></template>
