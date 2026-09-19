<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryx50ab7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ryx50ab7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:grin-beam" /></template>
