<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0a9vkbzg.css';
import '../../css/u/un2x9lbgo.css';
import '../../css/h/havk16b2m.css';
import '../../css/b/bi16igbmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="a0a9vkbzg"><path class="un2x9lbgo"/><path class="havk16b2m"/><path class="bi16igbmh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:connection" /></template>
