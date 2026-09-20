<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dautg90hb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dautg90hb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:goblet-line" /></template>
