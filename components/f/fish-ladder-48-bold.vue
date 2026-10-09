<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gf7o7sb5z.css';
import '../../css/s/shn1ydbrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gf7o7sb5z"/><path class="shn1ydbrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fish-ladder-48-bold" /></template>
