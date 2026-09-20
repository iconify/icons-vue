<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/x/x3ra-pn6i.css';
import '../../css/y/yx33g_bbf.css';
import '../../css/h/hzwio7bqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="x3ra-pn6i"/><path class="yx33g_bbf"/><path class="hzwio7bqu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:coding-files-network-folder" /></template>
