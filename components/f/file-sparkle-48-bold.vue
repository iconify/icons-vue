<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_pz3rxhk.css';
import '../../css/z/zfk_hjb8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y_pz3rxhk"/><path class="zfk_hjb8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:file-sparkle-48-bold" /></template>
