<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgcs14bkt.css';
import '../../css/o/o2vuw7npi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fgcs14bkt"/><path class="o2vuw7npi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gas-flare-48-bold" /></template>
