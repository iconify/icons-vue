<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6wqg-hrr.css';
import '../../css/c/ch_p76tdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s6wqg-hrr"/><path class="ch_p76tdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:landfill-gas-48-bold" /></template>
