<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mcicy0-2s.css';
import '../../css/e/euouyhb1v.css';
import '../../css/d/dltz39bdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="mcicy0-2s"/><path class="euouyhb1v"/><path class="dltz39bdr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gamepad-minimalistic-outline" /></template>
