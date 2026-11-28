<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5tyr8-bq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5tyr8-bq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:forklift" /></template>
