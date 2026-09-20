<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/p/p-9lnrvey.css';
import '../../css/w/wbfrzdxkc.css';
import '../../css/o/oe68fkbpc.css';
import '../../css/z/zf0lc5abk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="p-9lnrvey"/><path class="wbfrzdxkc"/><path class="oe68fkbpc"/><path class="zf0lc5abk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump-color:ai-generate-voice-robot-2-flat" /></template>
