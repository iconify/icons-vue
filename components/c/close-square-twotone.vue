<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gc8-4tb2b.css';
import '../../css/i/ickm1abrn.css';
import '../../css/z/zppuvabay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gc8-4tb2b"/><path class="ickm1abrn"/><path class="zppuvabay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:close-square-twotone" /></template>
