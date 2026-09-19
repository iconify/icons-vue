<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utgju3_rx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utgju3_rx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:card" /></template>
