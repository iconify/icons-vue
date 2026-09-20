<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o58hkebvg.css';
import '../../css/v/vm5aagbwz.css';
import '../../css/g/g3581pi_w.css';
import '../../css/n/nybh8pb1j.css';
import '../../css/v/v9yx2hhox.css';
import '../../css/w/w49j0rbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGvTVwgesb"><g class="o58hkebvg"><path class="vm5aagbwz"/><path class="g3581pi_w"/><path class="nybh8pb1j"/><path class="v9yx2hhox"/></g></mask></defs><path mask="url(#SVGvTVwgesb)" class="w49j0rbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:basket-alt-2-duotone-line" /></template>
