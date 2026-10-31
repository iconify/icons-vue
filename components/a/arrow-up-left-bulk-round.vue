<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry9yzu4ev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ry9yzu4ev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-up-left-bulk-round" /></template>
