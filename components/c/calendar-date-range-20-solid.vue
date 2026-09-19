<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cj-krkb_k.css';
import '../../css/a/a8x_xccwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cj-krkb_k"/><path clip-rule="evenodd" class="a8x_xccwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:calendar-date-range-20-solid" /></template>
