<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdn-nablh.css';
import '../../css/l/l4fpo9b9z.css';
import '../../css/z/z217erwyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zdn-nablh"/><path class="l4fpo9b9z"/><path class="z217erwyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-eslint-open" /></template>
