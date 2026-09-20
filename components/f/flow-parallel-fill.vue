<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxcz66biy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxcz66biy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:flow-parallel-fill" /></template>
