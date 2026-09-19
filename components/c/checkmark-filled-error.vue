<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c55vgcbjc.css';
import '../../css/h/h7v4f1b-l.css';
import '../../css/c/cyoweacxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c55vgcbjc"/><path class="h7v4f1b-l"/><path class="cyoweacxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:checkmark-filled-error" /></template>
