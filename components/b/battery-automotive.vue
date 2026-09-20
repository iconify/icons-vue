<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lu0q_f7sz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lu0q_f7sz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:battery-automotive" /></template>
