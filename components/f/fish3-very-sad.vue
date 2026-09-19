<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-g2gdbgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o-g2gdbgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:fish3-very-sad" /></template>
