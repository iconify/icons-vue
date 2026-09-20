<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpm3jpbta.css';
import '../../css/a/a4agvic7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":171.3,"height":60};
const content = `<path class="vpm3jpbta"/><path class="a4agvic7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:gong" /></template>
