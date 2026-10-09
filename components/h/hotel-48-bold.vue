<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pla65zbzp.css';
import '../../css/t/tmookwb_d.css';
import '../../css/s/sbar25bid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pla65zbzp"/><path class="tmookwb_d"/><path class="sbar25bid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hotel-48-bold" /></template>
