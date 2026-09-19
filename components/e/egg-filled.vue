<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1y6d1bwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1y6d1bwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:egg-filled" /></template>
