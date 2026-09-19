<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwibdw4bb.css';
import '../../css/g/g_dqbgbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwibdw4bb"/><path class="g_dqbgbri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-left-stroke-circle" /></template>
