<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmf4pnb7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="jmf4pnb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:arrows-to-dot" /></template>
