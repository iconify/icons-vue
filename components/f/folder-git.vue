<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/d/d34t52bcx.css';
import '../../css/o/obsscdhly.css';
import '../../css/w/wlpsfnrem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d34t52bcx"/><circle class="obsscdhly"/><path class="wlpsfnrem"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:folder-git" /></template>
