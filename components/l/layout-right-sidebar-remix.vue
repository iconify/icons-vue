<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sg3-g0s0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sg3-g0s0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:layout-right-sidebar-remix" /></template>
