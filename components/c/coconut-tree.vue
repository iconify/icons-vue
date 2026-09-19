<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv130ab-t.css';
import '../../css/g/gx85gbbnh.css';
import '../../css/e/e5o8hlb3d.css';
import '../../css/z/znzfcwbhp.css';
import '../../css/l/lvfkzebln.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGxpa09duy"><g class="hv130ab-t"><path class="gx85gbbnh"/><path class="e5o8hlb3d"/><path class="znzfcwbhp"/><path class="lvfkzebln"/></g></mask></defs><path mask="url(#SVGxpa09duy)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:coconut-tree" /></template>
