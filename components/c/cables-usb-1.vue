<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/s/s7ml_zbvx.css';
import '../../css/g/gu4o6xvsl.css';
import '../../css/e/eiee3q-fs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="s7ml_zbvx"/><path class="gu4o6xvsl"/><path class="eiee3q-fs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:cables-usb-1" /></template>
