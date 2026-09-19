<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy6_9_bea.css';
import '../../css/p/pmwtv-rax.css';
import '../../css/x/xai6gubor.css';
import '../../css/y/yosw-cc2e.css';
import '../../css/d/dbgippb-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="dy6_9_bea"/><path class="pmwtv-rax"/><path class="xai6gubor"/><path class="yosw-cc2e"/><path class="dbgippb-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:ghost" /></template>
