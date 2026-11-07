<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5_nvnutr.css';
import '../../css/x/xe9j-trbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5_nvnutr"/><path class="xe9j-trbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chevrons-left-right-bold" /></template>
