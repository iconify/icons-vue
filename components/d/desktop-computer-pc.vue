<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/n/ninwsxb1h.css';
import '../../css/k/kgw252bip.css';
import '../../css/m/mfuvyvbxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ninwsxb1h"/><path class="kgw252bip"/><path class="mfuvyvbxo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:desktop-computer-pc" /></template>
