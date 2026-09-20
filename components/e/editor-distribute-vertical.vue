<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwum7jbph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xwum7jbph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:editor-distribute-vertical" /></template>
