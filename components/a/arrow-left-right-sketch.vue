<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/lssi5abca.css';
import '../../css/m/m28utr75s.css';
import '../../css/e/evyvslb3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="lssi5abca wm-a"/><path class="m28utr75s wm-k"/><path class="evyvslb3y wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:arrow-left-right-sketch" /></template>
