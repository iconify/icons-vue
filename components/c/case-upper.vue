<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xff7nngrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xff7nngrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:case-upper" /></template>
