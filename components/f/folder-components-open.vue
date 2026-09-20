<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdrm33fiz.css';
import '../../css/w/we0aawlvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kdrm33fiz"/><path class="we0aawlvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-components-open" /></template>
