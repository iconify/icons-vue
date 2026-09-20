<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/d/dw9quyb8n.css';
import '../../css/w/wbknnx6bq.css';
import '../../css/x/xoczt_b8w.css';
import '../../css/d/dqty3c3-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="dw9quyb8n"/><path class="wbknnx6bq"/><path class="xoczt_b8w"/><path class="dqty3c3-r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:advertising-ad-browser" /></template>
