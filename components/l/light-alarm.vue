<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymxvme3fu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ymxvme3fu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:light-alarm" /></template>
