<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8s_7ub3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8s_7ub3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:edge" /></template>
