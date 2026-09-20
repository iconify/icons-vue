<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-16i40ew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-16i40ew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:car-off" /></template>
