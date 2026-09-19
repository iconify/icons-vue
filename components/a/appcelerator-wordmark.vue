<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x196-gi3w.css';
import '../../css/a/a04-1rvkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="x196-gi3w"/><path class="a04-1rvkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:appcelerator-wordmark" /></template>
