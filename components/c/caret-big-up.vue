<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dazixpb6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dazixpb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:caret-big-up" /></template>
