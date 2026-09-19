<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv130ab-t.css';
import '../../css/c/cu5xsb1ef.css';
import '../../css/e/e24rsjd1i.css';
import '../../css/g/g180g5bxx.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGvXQWmdhV"><g class="hv130ab-t"><rect class="cu5xsb1ef"/><path class="e24rsjd1i"/><path class="g180g5bxx"/></g></mask></defs><path mask="url(#SVGvXQWmdhV)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:f-n-key" /></template>
