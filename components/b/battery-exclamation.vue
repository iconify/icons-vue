<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ul432mbdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ul432mbdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:battery-exclamation" /></template>
