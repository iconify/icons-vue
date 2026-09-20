<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q21hny20d.css';
import '../../css/m/mcr7zubuf.css';
import '../../css/s/s0l0zu_qn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q21hny20d"/><path class="mcr7zubuf"/><path class="s0l0zu_qn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:line" /></template>
