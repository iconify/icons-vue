<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/h/ht783wbsg.css';
import '../../css/q/q7h2v6bia.css';
import '../../css/z/zx5ptubbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ht783wbsg"/><path class="q7h2v6bia"/><path class="zx5ptubbn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:code-monitor-1-flat" /></template>
