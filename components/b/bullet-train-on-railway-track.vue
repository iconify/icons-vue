<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sokfneber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sokfneber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bullet-train-on-railway-track" /></template>
