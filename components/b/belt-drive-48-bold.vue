<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k48mo0bik.css';
import '../../css/u/u1ifhyb-o.css';
import '../../css/t/t7x_kqnwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k48mo0bik"/><path class="u1ifhyb-o"/><path class="t7x_kqnwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:belt-drive-48-bold" /></template>
