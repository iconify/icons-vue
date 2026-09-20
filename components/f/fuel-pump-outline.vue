<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzk4g4ahp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzk4g4ahp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fuel-pump-outline" /></template>
