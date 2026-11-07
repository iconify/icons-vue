<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbp17eb1m.css';
import '../../css/x/xza96qbbg.css';
import '../../css/g/grj_h9ayp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbp17eb1m"/><path class="xza96qbbg"/><path clip-rule="evenodd" class="grj_h9ayp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:face-scan-circle-outline" /></template>
