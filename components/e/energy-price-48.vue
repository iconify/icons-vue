<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5b4wqbaq.css';
import '../../css/s/st1b0k75a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q5b4wqbaq"/><path class="st1b0k75a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:energy-price-48" /></template>
