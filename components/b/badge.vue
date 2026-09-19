<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnkfl--xj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jnkfl--xj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:badge" /></template>
