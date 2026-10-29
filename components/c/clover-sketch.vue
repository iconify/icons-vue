<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/ploj10bjh.css';
import '../../css/i/is9ah22yz.css';
import '../../css/q/qvltmxb0q.css';
import '../../css/b/b9pyc9jsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ploj10bjh wm-k"/><path class="is9ah22yz wm-a"/><path class="qvltmxb0q wm-k"/><path class="b9pyc9jsm wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:clover-sketch" /></template>
