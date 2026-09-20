<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujuhc5bhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ujuhc5bhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:intersect-line" /></template>
