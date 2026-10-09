<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tby_lo-nb.css';
import '../../css/e/e33pt4b0g.css';
import '../../css/p/ps6ai49ok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tby_lo-nb"/><path class="e33pt4b0g"/><path class="ps6ai49ok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gauge-20" /></template>
