<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/o5leul9ao.css';
import '../../css/p/p4bxscbjk.css';
import '../../css/z/zuqzax3uu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="o5leul9ao"/><path class="p4bxscbjk"/><path class="zuqzax3uu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:git-commit-sketch" /></template>
