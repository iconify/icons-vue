<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yd931_gmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yd931_gmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:glasses-remix" /></template>
