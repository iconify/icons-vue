<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmrroccsk.css';
import '../../css/n/n3g_7jbbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmrroccsk"/><path class="n3g_7jbbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:job-search-man-bold" /></template>
