<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgga7abld.css';
import '../../css/p/p9pavjj4d.css';
import '../../css/l/ln6f3q98l.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGvq32Ydak"><g class="cgga7abld"><path class="p9pavjj4d"/><path class="ln6f3q98l"/></g></mask></defs><path mask="url(#SVGvq32Ydak)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:gymnastics-one" /></template>
