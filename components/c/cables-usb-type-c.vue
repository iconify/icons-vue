<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/e/epk0drb8m.css';
import '../../css/y/ynoqnxpwc.css';
import '../../css/i/i9g5gccvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="epk0drb8m"/><path class="ynoqnxpwc"/><path class="i9g5gccvv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:cables-usb-type-c" /></template>
