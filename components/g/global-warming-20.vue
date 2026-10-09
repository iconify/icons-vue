<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l80gl972s.css';
import '../../css/q/qyw8labld.css';
import '../../css/j/jo8s-ccbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l80gl972s"/><path class="qyw8labld"/><path class="jo8s-ccbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:global-warming-20" /></template>
