<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lih_j9_oa.css';
import '../../css/d/debdggzbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lih_j9_oa"/><path class="debdggzbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-taskfile-open" /></template>
