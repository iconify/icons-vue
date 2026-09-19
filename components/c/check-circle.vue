<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtnykb6qt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtnykb6qt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:check-circle" /></template>
