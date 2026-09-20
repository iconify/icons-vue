<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tol6492tp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tol6492tp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cash-off" /></template>
