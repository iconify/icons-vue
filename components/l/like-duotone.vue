<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qh68rnblk.css';
import '../../css/g/g45mtmdnj.css';
import '../../css/t/tcccckbck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qh68rnblk"/><path class="g45mtmdnj"/><path class="tcccckbck"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:like-duotone" /></template>
