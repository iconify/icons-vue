<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ove_r8gba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ove_r8gba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:debug-breakpoint-unsupported" /></template>
