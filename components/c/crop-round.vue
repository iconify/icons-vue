<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jv3ylgrfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jv3ylgrfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:crop-round" /></template>
