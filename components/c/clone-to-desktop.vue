<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb-nc6b2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="zb-nc6b2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:clone-to-desktop" /></template>
