<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/roiy15max.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="roiy15max"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:full-screen-osx-remix" /></template>
