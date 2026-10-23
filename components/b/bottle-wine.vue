<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqdzkgbnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqdzkgbnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:bottle-wine" /></template>
