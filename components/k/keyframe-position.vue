<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpir9yb7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dpir9yb7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:keyframe-position" /></template>
