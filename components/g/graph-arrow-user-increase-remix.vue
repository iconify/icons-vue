<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2r9gabou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o2r9gabou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:graph-arrow-user-increase-remix" /></template>
