<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j373qu83g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="j373qu83g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:hand-pointer" /></template>
