<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dw0jjfbol.css';
import '../../css/a/a-uf0ibir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dw0jjfbol"/><path class="a-uf0ibir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:checkbox-indeterminate-filled" /></template>
