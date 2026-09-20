<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0_11wbtm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0_11wbtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grid-circles-check-sharp" /></template>
