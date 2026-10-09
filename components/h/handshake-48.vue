<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1v0ij09t.css';
import '../../css/c/cv6p3wbsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p1v0ij09t"/><path class="cv6p3wbsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:handshake-48" /></template>
