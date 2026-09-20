<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh4423hht.css';
import '../../css/h/hezb7ebtf.css';
import '../../css/p/pdjh1hb7i.css';
import '../../css/p/p8n1gxb1t.css';
import '../../css/m/mw7rs_yrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zh4423hht"/><path class="hezb7ebtf"/><path class="pdjh1hb7i"/><path clip-rule="evenodd" class="p8n1gxb1t"/><path clip-rule="evenodd" class="mw7rs_yrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-src-tauri-open" /></template>
