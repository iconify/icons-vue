<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcwqhmm_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fcwqhmm_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:fishing-rod" /></template>
