<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oeb5a7bpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="oeb5a7bpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:clipboard-list" /></template>
