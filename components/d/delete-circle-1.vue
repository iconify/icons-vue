<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_04xsbam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_04xsbam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber-color:delete-circle-1" /></template>
