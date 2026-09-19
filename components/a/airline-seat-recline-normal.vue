<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_tdmcb6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":424};
const content = `<path class="u_tdmcb6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:airline-seat-recline-normal" /></template>
