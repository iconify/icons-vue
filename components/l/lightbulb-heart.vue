<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk_4jabvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dk_4jabvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:lightbulb-heart" /></template>
