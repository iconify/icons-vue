<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agrarus0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agrarus0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:align-right" /></template>
