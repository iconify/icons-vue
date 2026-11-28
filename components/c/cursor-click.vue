<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-v_dpbad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-v_dpbad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cursor-click" /></template>
