<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/t/tr97dznbu.css';
import '../../css/w/wgr3atlzf.css';
import '../../css/h/hye_smbec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="tr97dznbu"/><path class="wgr3atlzf"/><path class="hye_smbec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:edit-pen-write-paper" /></template>
