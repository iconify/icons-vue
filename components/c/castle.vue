<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt6_fab0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dt6_fab0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:castle" /></template>
