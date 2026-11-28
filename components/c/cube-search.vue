<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu94njbui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cu94njbui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cube-search" /></template>
