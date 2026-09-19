<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0a9vkbzg.css';
import '../../css/g/gqzrcgbas.css';
import '../../css/t/t3es0cbgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="a0a9vkbzg"><path class="gqzrcgbas"/><path clip-rule="evenodd" class="t3es0cbgl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:hand-up" /></template>
