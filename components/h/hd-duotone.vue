<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/phgbpj4vk.css';
import '../../css/f/f20lr8brg.css';
import '../../css/s/s805e4aqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="phgbpj4vk"/><path class="f20lr8brg"/><path class="s805e4aqh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:hd-duotone" /></template>
