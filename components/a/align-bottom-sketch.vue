<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/jrmib2jjd.css';
import '../../css/u/uah0ipwxe.css';
import '../../css/z/zghmjfooh.css';
import '../../css/x/xkapnbb1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="jrmib2jjd"/><path class="uah0ipwxe wm-k"/><path class="wm-k zghmjfooh"/><path class="wm-a xkapnbb1l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:align-bottom-sketch" /></template>
