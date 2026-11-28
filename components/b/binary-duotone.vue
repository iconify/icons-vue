<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlh01qbdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mlh01qbdo primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:binary-duotone" /></template>
