<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpeh0zdbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="vpeh0zdbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:arrow-four-way" /></template>
