<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij1t_tb4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ij1t_tb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:file" /></template>
