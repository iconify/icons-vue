<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/b9qbfkbhi.css';
import '../../css/x/xa97w_bpi.css';
import '../../css/a/a2wzrrckz.css';
import '../../css/z/zixf3ibhr.css';
import '../../css/g/gsifqvbui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="b9qbfkbhi"/><path class="wm-k xa97w_bpi"/><path class="a2wzrrckz wm-a"/><path class="wm-k zixf3ibhr"/><path class="gsifqvbui wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:book-open-check-sketch" /></template>
