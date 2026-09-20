<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sf1mlabzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sf1mlabzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:dashboard-1-remix" /></template>
