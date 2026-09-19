<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kobakmnrv.css';
import '../../css/r/rcci-d4wx.css';
import '../../css/b/b197rfn0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kobakmnrv"/><path class="rcci-d4wx"/><path class="b197rfn0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:italianflag" /></template>
