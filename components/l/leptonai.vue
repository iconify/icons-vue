<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/m/ma3i4nbnb.css';
import '../../css/z/zpdyuobzf.css';
import '../../css/b/bv9t2ie8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="n1lsf0bnc"><path clip-rule="evenodd" class="ma3i4nbnb"/><path clip-rule="evenodd" class="zpdyuobzf"/><path class="bv9t2ie8k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:leptonai" /></template>
