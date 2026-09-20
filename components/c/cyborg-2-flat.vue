<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/y/yvjc3r64y.css';
import '../../css/d/dpxq9ov5b.css';
import '../../css/t/tgbgf7-4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="yvjc3r64y"/><path class="dpxq9ov5b"/><path class="tgbgf7-4k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:cyborg-2-flat" /></template>
