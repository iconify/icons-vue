<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydmsz_o0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ydmsz_o0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:handwashing" /></template>
