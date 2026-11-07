<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzryhs1ak.css';
import '../../css/o/on5h-v5us.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tzryhs1ak"/><path class="on5h-v5us"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:export-outline" /></template>
