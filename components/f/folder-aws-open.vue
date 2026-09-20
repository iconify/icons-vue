<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aylyh4brw.css';
import '../../css/b/bpmtllbfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aylyh4brw"/><path class="bpmtllbfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-aws-open" /></template>
