<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bix5dccyb.css';
import '../../css/u/ue-8cqbhf.css';
import '../../css/w/wsd75ceda.css';
import '../../css/z/zsuclwbnx.css';
import '../../css/k/kspoj7vnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="bix5dccyb"/><path clip-rule="evenodd" class="ue-8cqbhf"/><path clip-rule="evenodd" class="wsd75ceda"/><path class="zsuclwbnx"/><path clip-rule="evenodd" class="kspoj7vnd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:arrow-left-circle-off" /></template>
