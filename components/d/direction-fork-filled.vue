<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emfgklaqt.css';
import '../../css/c/cvwa4ha8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="emfgklaqt"/><path class="cvwa4ha8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:direction-fork-filled" /></template>
