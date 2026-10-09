<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agimoob8o.css';
import '../../css/m/m8c88eb6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="agimoob8o"/><path class="m8c88eb6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:airplay-48" /></template>
