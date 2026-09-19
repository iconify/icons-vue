<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up4hb1bjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="up4hb1bjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:file-earmark-arrow-down-fill" /></template>
