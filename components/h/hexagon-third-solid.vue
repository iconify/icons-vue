<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjubgvz7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjubgvz7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:hexagon-third-solid" /></template>
