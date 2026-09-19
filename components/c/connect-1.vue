<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfj60beug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="tfj60beug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:connect-1" /></template>
