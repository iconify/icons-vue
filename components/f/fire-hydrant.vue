<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l47w35-sy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="l47w35-sy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:fire-hydrant" /></template>
