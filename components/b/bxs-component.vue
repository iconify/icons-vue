<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlvh-wb2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rlvh-wb2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-component" /></template>
