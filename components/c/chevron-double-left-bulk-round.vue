<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3xt6ccoj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3xt6ccoj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chevron-double-left-bulk-round" /></template>
