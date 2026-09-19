<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xldjoowuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xldjoowuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:chevrons-expand-vertical-from-line" /></template>
