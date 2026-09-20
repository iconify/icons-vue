<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chz62cc3y.css';
import '../../css/m/mxksfsbhx.css';
import '../../css/l/lg4yc5rft.css';
import '../../css/x/xhj_v8b4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chz62cc3y"/><path class="mxksfsbhx"/><path class="lg4yc5rft"/><path class="xhj_v8b4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:google-hangouts-alt" /></template>
