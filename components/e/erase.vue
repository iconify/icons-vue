<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysmh8gbnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="ysmh8gbnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:erase" /></template>
