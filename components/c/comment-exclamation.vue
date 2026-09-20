<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kc_ggwbfn.css';
import '../../css/n/nzf-rrbnz.css';
import '../../css/u/ups1br8xq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kc_ggwbfn"/><path class="nzf-rrbnz"/><circle class="ups1br8xq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:comment-exclamation" /></template>
