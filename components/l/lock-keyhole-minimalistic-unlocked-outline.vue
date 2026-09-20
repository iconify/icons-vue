<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/p6ifo1irq.css';
import '../../css/i/ir9jvbdqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="p6ifo1irq"/><path clip-rule="evenodd" class="ir9jvbdqh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:lock-keyhole-minimalistic-unlocked-outline" /></template>
