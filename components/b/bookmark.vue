<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w17hi6fgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w17hi6fgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:bookmark" /></template>
