<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcr8hnbtp.css';
import '../../css/o/ohfs0hakv.css';
import '../../css/h/hwanmkeov.css';
import '../../css/g/gkefinb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcr8hnbtp"/><path class="ohfs0hakv"/><path class="hwanmkeov"/><path clip-rule="evenodd" class="gkefinb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:article-share-duotone" /></template>
