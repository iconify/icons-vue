<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7ow20d_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7ow20d_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:align-objects-left" /></template>
