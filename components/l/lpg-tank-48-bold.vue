<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc7b7e4ab.css';
import '../../css/u/un07r_bjv.css';
import '../../css/p/pdn0d5lux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bc7b7e4ab"/><path class="un07r_bjv"/><path class="pdn0d5lux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lpg-tank-48-bold" /></template>
