<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pk3045bun.css';
import '../../css/q/q0fujjtaq.css';
import '../../css/g/g4hu-_ntn.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGwfhVHbgs"><g class="ft5dv1b6b"><path class="pk3045bun"/><path class="q0fujjtaq"/><path class="g4hu-_ntn"/></g></mask></defs><path mask="url(#SVGwfhVHbgs)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:battery-full" /></template>
