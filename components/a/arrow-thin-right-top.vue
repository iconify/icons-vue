<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/neeg-jrvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="neeg-jrvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:arrow-thin-right-top" /></template>
