<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_zzykbds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_zzykbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:arrow-dot-corner-left-1" /></template>
