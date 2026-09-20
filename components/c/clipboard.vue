<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp63vz7xa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xp63vz7xa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:clipboard" /></template>
