<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-kqxybqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="x-kqxybqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:bone" /></template>
