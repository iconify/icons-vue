<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/og04z_gpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="og04z_gpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cube-plus" /></template>
