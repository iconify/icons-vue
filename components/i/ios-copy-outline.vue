<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhnf1kbvb.css';
import '../../css/c/ccs4fgbgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rhnf1kbvb"/><path class="ccs4fgbgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-copy-outline" /></template>
