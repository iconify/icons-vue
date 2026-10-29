<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/bqi8s4bgh.css';
import '../../css/p/p3y-97bfh.css';
import '../../css/l/lo-bdo53p.css';
import '../../css/t/tcjvbpb5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="bqi8s4bgh wm-k"/><path class="p3y-97bfh wm-shadow"/><path class="lo-bdo53p wm-k"/><path class="tcjvbpb5r wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:gamepad-engrave" /></template>
