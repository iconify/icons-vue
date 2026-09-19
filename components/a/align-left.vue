<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h37_n9-5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="h37_n9-5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:align-left" /></template>
