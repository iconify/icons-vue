<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud2s2km0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ud2s2km0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-collapse-horizontal-two-tone" /></template>
