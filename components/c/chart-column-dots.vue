<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdg3wxbvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdg3wxbvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:chart-column-dots" /></template>
