<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vng_kgbvl.css';
import '../../css/k/ke73g8b7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vng_kgbvl"/><path class="ke73g8b7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:energy-efficiency-20" /></template>
