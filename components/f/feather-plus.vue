<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2hc067ou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k2hc067ou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:feather-plus" /></template>
