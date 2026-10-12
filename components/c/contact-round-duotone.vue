<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dp65jjfxh.css';
import '../../css/r/rgggbcbui.css';
import '../../css/s/s1a2eew1e.css';
import '../../css/z/z1ppekb6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="dp65jjfxh"/><path class="rgggbcbui"/><path class="s1a2eew1e"/><path clip-rule="evenodd" class="z1ppekb6l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:contact-round-duotone" /></template>
