<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s37u5-ydv.css';
import '../../css/i/i_82ckbxh.css';
import '../../css/k/kbdolkbrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s37u5-ydv"/><path class="i_82ckbxh"/><circle class="kbdolkbrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-circleci-open" /></template>
