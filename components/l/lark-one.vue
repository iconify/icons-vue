<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/uondj3csi.css';
import '../../css/i/iz9qeihpv.css';
import '../../css/b/bpqpvpasa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="uondj3csi"/><path clip-rule="evenodd" class="iz9qeihpv"/><path class="bpqpvpasa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:lark-one" /></template>
