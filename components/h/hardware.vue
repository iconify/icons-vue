<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjh1bacdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":17};
const content = `<path class="qjh1bacdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:hardware" /></template>
