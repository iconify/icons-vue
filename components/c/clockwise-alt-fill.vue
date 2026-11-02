<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmzkdoamb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmzkdoamb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clockwise-alt-fill" /></template>
