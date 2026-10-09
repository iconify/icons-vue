<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmoocjcae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pmoocjcae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:command-48-bold" /></template>
