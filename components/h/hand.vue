<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xahq9btrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="xahq9btrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:hand" /></template>
