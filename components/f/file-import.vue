<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p07tmccvv.css';
import '../../css/o/o0s3prb3b.css';
import '../../css/h/h5i3i5jgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="p07tmccvv"><path class="o0s3prb3b"/><path class="h5i3i5jgf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:file-import" /></template>
