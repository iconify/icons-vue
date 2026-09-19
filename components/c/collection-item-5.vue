<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e54zhh65x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":480};
const content = `<path class="e54zhh65x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:collection-item-5" /></template>
