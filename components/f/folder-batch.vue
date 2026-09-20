<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aiap8ebun.css';
import '../../css/l/lommj4luf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="aiap8ebun"/><path class="lommj4luf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-batch" /></template>
