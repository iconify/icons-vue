<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjeto3wbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="yjeto3wbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:gear-1" /></template>
