<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f26nuccua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f26nuccua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:down" /></template>
