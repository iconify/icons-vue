<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kko9ybv0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kko9ybv0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:debug-breakpoint-conditional" /></template>
