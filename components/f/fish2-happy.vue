<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oq1j-2omy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oq1j-2omy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:fish2-happy" /></template>
