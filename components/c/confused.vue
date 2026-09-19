<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn7-6cg6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yn7-6cg6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:confused" /></template>
