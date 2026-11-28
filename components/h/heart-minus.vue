<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_ci9bxid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_ci9bxid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:heart-minus" /></template>
