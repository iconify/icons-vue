<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2klj1btq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2klj1btq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:copy-plus-round" /></template>
