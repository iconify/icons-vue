<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_lpk1qhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_lpk1qhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:chevrons-to-axis-vertical" /></template>
