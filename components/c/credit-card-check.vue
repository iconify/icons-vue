<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/an7obwbhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="an7obwbhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:credit-card-check" /></template>
