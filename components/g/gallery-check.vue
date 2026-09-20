<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ja7ltjp0f.css';
import '../../css/n/n1lsf0bnc.css';
import '../../css/b/btlxfkbwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVGeEBWIcGE" class="ja7ltjp0f"/></defs><g clip-rule="evenodd" class="n1lsf0bnc"><path class="btlxfkbwh"/><use href="#SVGeEBWIcGE"/><use href="#SVGeEBWIcGE"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:gallery-check" /></template>
