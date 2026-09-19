<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtbsphbxc.css';
import '../../css/o/ozp-gmbzh.css';
import '../../css/d/dneqyku5s.css';
import '../../css/a/a037hmb_i.css';
import '../../css/a/apogh5b8k.css';
import '../../css/g/gktr2bb-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gtbsphbxc"/><path class="ozp-gmbzh"/><path class="dneqyku5s"/><path class="a037hmb_i"/><path class="apogh5b8k"/><path class="gktr2bb-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:hatchingchick" /></template>
