<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ik5-7ezyb.css';
import '../../css/r/rvju-3bng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ik5-7ezyb"/><path class="rvju-3bng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:file-json" /></template>
