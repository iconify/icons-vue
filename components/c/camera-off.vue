<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmsn97bpu.css';
import '../../css/e/eg7twmghe.css';
import '../../css/p/p_qtwib1e.css';
import '../../css/u/u803lmbik.css';
import '../../css/c/c1hfj9brg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tmsn97bpu wm-k"/><path class="eg7twmghe wm-k"/><path class="p_qtwib1e wm-a"/><path class="u803lmbik wm-s"/><path class="c1hfj9brg wm-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:camera-off" /></template>
