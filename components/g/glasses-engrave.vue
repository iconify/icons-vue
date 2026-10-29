<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/teyry0bvj.css';
import '../../css/h/h8t4uobjx.css';
import '../../css/e/eznhzablb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="teyry0bvj"/><path class="h8t4uobjx wm-shadow"/><path class="eznhzablb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:glasses-engrave" /></template>
