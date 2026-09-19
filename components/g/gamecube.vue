<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vowd07ird.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vowd07ird"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:gamecube" /></template>
