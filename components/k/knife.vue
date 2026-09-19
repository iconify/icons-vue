<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw9cx653v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="iw9cx653v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:knife" /></template>
