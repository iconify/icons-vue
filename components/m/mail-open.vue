<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0a9vkbzg.css';
import '../../css/e/e97cal7kt.css';
import '../../css/h/hzgy6wbai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="a0a9vkbzg"><path class="e97cal7kt"/><path class="hzgy6wbai"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:mail-open" /></template>
