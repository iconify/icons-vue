<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/m/m0xrrzbhk.css';
import '../../css/a/a188s0iwo.css';
import '../../css/q/qwkyr7biq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="m0xrrzbhk"/><path class="a188s0iwo"/><path class="qwkyr7biq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:folder-plus" /></template>
