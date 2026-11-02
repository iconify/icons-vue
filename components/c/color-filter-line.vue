<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iguu3q8az.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iguu3q8az"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:color-filter-line" /></template>
