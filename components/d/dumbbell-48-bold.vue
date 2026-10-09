<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl8r3viay.css';
import '../../css/q/qdpkq-bcf.css';
import '../../css/l/l89fhnblb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vl8r3viay"/><path class="qdpkq-bcf"/><path class="l89fhnblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dumbbell-48-bold" /></template>
