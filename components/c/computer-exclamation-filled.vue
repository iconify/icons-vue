<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flrbi8fuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="flrbi8fuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:computer-exclamation-filled" /></template>
