<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcn1mjbjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="qcn1mjbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:data-arrow-down" /></template>
