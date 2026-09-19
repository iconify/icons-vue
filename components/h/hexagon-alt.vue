<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ri_0_bfkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ri_0_bfkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:hexagon-alt" /></template>
