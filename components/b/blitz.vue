<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_o2gabit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_o2gabit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:blitz" /></template>
