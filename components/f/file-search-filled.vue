<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdmzqfeyj.css';
import '../../css/z/zt3xb3pls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdmzqfeyj"/><path class="zt3xb3pls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:file-search-filled" /></template>
