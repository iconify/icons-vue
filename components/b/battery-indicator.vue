<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnndfeb9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnndfeb9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:battery-indicator" /></template>
