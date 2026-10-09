<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9c993b2t.css';
import '../../css/q/q403o2bvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x9c993b2t"/><path class="q403o2bvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dishwasher-48-bold" /></template>
