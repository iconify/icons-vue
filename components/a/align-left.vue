<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyeo_epso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cyeo_epso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:align-left" /></template>
