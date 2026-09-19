<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uo5q_abex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uo5q_abex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:car-parking-01" /></template>
