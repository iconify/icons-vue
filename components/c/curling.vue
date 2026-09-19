<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2pd2dxzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2pd2dxzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:curling" /></template>
