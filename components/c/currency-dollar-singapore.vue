<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0l8uz36w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l0l8uz36w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:currency-dollar-singapore" /></template>
