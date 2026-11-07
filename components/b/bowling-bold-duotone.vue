<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnb90nbxf.css';
import '../../css/q/qhrokpb5f.css';
import '../../css/k/kr6tfbc9g.css';
import '../../css/h/ht1vpi3ki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnb90nbxf"/><path class="qhrokpb5f"/><path class="kr6tfbc9g"/><path class="ht1vpi3ki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bowling-bold-duotone" /></template>
