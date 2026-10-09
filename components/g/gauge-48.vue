<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmmt3ebdz.css';
import '../../css/f/ftjyp7crf.css';
import '../../css/q/qeutyabff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wmmt3ebdz"/><path class="ftjyp7crf"/><path class="qeutyabff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gauge-48" /></template>
