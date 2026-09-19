<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zx53fjb6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zx53fjb6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:file-dollar" /></template>
