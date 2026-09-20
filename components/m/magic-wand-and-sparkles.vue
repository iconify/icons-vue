<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwnz-qbcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jwnz-qbcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:magic-wand-and-sparkles" /></template>
