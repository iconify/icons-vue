<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u64wme6op.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u64wme6op"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:dresser-outline" /></template>
