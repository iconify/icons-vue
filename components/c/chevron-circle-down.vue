<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgxi_rbmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgxi_rbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:chevron-circle-down" /></template>
