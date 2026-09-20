<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bxu-ixbxe.css';
import '../../css/v/v8vm-z-vm.css';
import '../../css/x/xwni9mcbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bxu-ixbxe"/><path class="v8vm-z-vm"/><circle class="xwni9mcbw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:bell-dot" /></template>
