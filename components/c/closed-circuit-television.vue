<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jq3_rzi9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jq3_rzi9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:closed-circuit-television" /></template>
