<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqrd0s_-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqrd0s_-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:filter-linear" /></template>
