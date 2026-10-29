<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vx2_23bwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vx2_23bwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:arrow-big-up-solid" /></template>
