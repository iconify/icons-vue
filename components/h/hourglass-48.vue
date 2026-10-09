<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbfsj092o.css';
import '../../css/j/jc99_77ng.css';
import '../../css/n/n994qc39b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kbfsj092o"/><path class="jc99_77ng"/><path class="n994qc39b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hourglass-48" /></template>
