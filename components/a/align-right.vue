<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcyt4bref.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="fcyt4bref"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:align-right" /></template>
