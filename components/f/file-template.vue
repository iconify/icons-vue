<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2k2s4b0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="b2k2s4b0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:file-template" /></template>
