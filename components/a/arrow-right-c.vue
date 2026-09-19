<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1j2x1sim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k1j2x1sim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:arrow-right-c" /></template>
