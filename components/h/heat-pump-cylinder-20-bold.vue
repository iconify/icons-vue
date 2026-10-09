<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s69k6bb7h.css';
import '../../css/o/ofyi6pbuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s69k6bb7h"/><path class="ofyi6pbuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-pump-cylinder-20-bold" /></template>
