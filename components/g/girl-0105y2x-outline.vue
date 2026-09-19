<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jm5x7_bdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jm5x7_bdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:girl-0105y2x-outline" /></template>
