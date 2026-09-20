<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwt_mwbit.css';
import '../../css/z/z7xvm0bee.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/b/b7jaab_wx.css';
import '../../css/z/z0dzo430t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="xwt_mwbit"/><path class="z7xvm0bee"/><g class="ij2x_72vy"><path class="b7jaab_wx"/><path class="z0dzo430t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:fried-shrimp" /></template>
