<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kj-p4p_9x.css';
import '../../css/u/uavtgqbwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kj-p4p_9x"/><path class="uavtgqbwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chevrons-down-20-bold" /></template>
