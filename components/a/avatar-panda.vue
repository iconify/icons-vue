<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kuuho-btb.css';
import '../../css/r/ruvbxe6ge.css';
import '../../css/u/upnry9bsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kuuho-btb wm-k"/><path class="ruvbxe6ge wm-shine"/><path class="upnry9bsk wm-shine"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-lunar:avatar-panda" /></template>
