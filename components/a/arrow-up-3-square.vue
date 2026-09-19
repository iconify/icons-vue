<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfl5-fb6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfl5-fb6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-up-3-square" /></template>
