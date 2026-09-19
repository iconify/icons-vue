<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da1b7yb7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="da1b7yb7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:bowling" /></template>
