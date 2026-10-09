<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqu-jov0y.css';
import '../../css/i/i2hezybim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kqu-jov0y"/><path class="i2hezybim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:depot-charging-48-bold" /></template>
