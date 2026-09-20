<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpgyb1h7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="kpgyb1h7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-arrows-expand-diagonal-1-expand-resize-bigger-diagonal-smaller-size-arrow-arrows-big" /></template>
