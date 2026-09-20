<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2tq1fb0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j2tq1fb0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-cpp" /></template>
