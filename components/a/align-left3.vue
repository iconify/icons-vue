<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx8nb4mqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lx8nb4mqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:align-left3" /></template>
