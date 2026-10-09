<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhg7ko28s.css';
import '../../css/y/ywq58thzo.css';
import '../../css/o/oh1_vxmzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lhg7ko28s"/><path class="ywq58thzo"/><path class="oh1_vxmzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:crew-transfer-vessel-20" /></template>
