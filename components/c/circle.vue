<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwqu0vbxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<circle class="iwqu0vbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:circle" /></template>
