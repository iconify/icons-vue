<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/reu1yxf8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":17};
const content = `<path class="reu1yxf8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:circle-control-pad" /></template>
