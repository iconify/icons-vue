<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ooo659baw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ooo659baw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:chevrons-from-axis-dashed-horizontal" /></template>
