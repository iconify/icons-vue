<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctp10hf8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="ctp10hf8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:bubble-message-dot-2" /></template>
