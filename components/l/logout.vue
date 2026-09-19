<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi0-5pbvt.css';
import '../../css/z/z6nnhfbxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bi0-5pbvt"/><path class="z6nnhfbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:logout" /></template>
