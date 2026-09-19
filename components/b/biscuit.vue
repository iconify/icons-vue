<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ago6k6csm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ago6k6csm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:biscuit" /></template>
