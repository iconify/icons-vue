<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p9-zrkb4g.css';
import '../../css/l/lio31ybkz.css';
import '../../css/a/au1g5-box.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="p9-zrkb4g"/><path class="lio31ybkz"/><path class="au1g5-box"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:logo-miniprogram" /></template>
