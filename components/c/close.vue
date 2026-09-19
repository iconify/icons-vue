<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg_puf8nt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="eg_puf8nt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:close" /></template>
