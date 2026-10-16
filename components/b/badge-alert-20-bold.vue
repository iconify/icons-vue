<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-q-p1bwi.css';
import '../../css/k/kqh_8ib1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m-q-p1bwi"/><path class="kqh_8ib1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:badge-alert-20-bold" /></template>
