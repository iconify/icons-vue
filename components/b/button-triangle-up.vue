<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygj31lgsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="ygj31lgsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:button-triangle-up" /></template>
