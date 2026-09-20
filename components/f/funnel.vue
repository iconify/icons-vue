<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3vhv3bxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="i3vhv3bxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:funnel" /></template>
