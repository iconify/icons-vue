<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/b/byxv1wbzp.css';
import '../../css/d/d24zw2byv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="byxv1wbzp"/><path class="d24zw2byv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:folder-library" /></template>
