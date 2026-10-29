<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/ui_oqub5z.css';
import '../../css/y/y_jfvcwtp.css';
import '../../css/l/l484bmbsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ui_oqub5z"/><path class="wm-shadow y_jfvcwtp"/><path class="l484bmbsu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:folder-engrave" /></template>
