<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pk3045bun.css';
import '../../css/q/q0fujjtaq.css';
import '../../css/h/hiss9szrd.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG85M9KeJC"><g class="ft5dv1b6b"><path class="pk3045bun"/><path class="q0fujjtaq"/><path class="hiss9szrd"/></g></mask></defs><path mask="url(#SVG85M9KeJC)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:battery-working" /></template>
