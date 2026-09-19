<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2l6rf1jc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v2l6rf1jc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:bandage" /></template>
