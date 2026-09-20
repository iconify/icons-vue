<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pio0e7bsu.css';
import '../../css/w/wdohmybjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pio0e7bsu"/><path class="wdohmybjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:id-card" /></template>
