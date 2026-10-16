<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv4p-irnn.css';
import '../../css/m/moo4i7zmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pv4p-irnn"/><path class="moo4i7zmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:charger-dual-20" /></template>
