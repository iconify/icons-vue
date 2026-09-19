<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbhtpfbxo.css';
import '../../css/d/dv2xvhb0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xbhtpfbxo"/><path class="dv2xvhb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:https" /></template>
