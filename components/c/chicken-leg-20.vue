<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0gbnw5mt.css';
import '../../css/n/nj8qf_mxd.css';
import '../../css/s/s8v6w-jez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s0gbnw5mt"/><path class="nj8qf_mxd"/><path class="s8v6w-jez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chicken-leg-20" /></template>
