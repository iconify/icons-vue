<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjqoj_b0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="zjqoj_b0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:gas-station" /></template>
