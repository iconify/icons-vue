<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3lph30dl.css';
import '../../css/y/y2dgydb7o.css';
import '../../css/a/a2im80b3m.css';
import '../../css/g/gj5isf39e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path class="y2dgydb7o"/><path class="a2im80b3m"/><path class="gj5isf39e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:afferent-two" /></template>
