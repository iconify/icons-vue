<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cza95wglm.css';
import '../../css/m/mrmylhbxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cza95wglm"/><path class="mrmylhbxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:bookmark-double-filled" /></template>
