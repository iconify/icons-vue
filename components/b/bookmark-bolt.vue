<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb4_wab6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tb4_wab6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bookmark-bolt" /></template>
