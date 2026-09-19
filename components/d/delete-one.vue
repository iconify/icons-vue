<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/n/nybc2db3k.css';
import '../../css/h/hatha3nri.css';
import '../../css/t/tw5ngbukx.css';
import '../../css/h/h5amn9btw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="nybc2db3k"/><path class="hatha3nri"/><path clip-rule="evenodd" class="tw5ngbukx"/><path class="h5amn9btw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:delete-one" /></template>
