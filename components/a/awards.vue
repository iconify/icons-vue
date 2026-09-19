<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kniqe2b7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kniqe2b7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:awards" /></template>
