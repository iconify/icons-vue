<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/w4cznxjwh.css';
import '../../css/i/irbpncu7y.css';
import '../../css/b/be5nhjdal.css';
import '../../css/p/pcqn0-bgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="w4cznxjwh wm-k"/><path class="irbpncu7y wm-a"/><path class="be5nhjdal wm-k"/><path class="pcqn0-bgs wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:euro-sketch" /></template>
