<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmsryhb8r.css';
import '../../css/r/rmujqn65w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wmsryhb8r"/><path class="rmujqn65w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:apple-20" /></template>
