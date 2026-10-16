<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmty_lb2n.css';
import '../../css/b/b_dryruwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kmty_lb2n"/><path class="b_dryruwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gas-detector-48-bold" /></template>
