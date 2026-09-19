<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/p/pyyqe43jj.css';
import '../../css/y/ysz-sj5au.css';
import '../../css/k/kopzj4bjj.css';
import '../../css/s/s_3nrbdvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="pyyqe43jj"/><path class="ysz-sj5au"/><path class="kopzj4bjj"/><path class="s_3nrbdvv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:lock-open-outline" /></template>
