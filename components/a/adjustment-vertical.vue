<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oe-7uybqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="oe-7uybqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:adjustment-vertical" /></template>
