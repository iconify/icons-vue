<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/i/ir4dw3bpl.css';
import '../../css/y/y2orggbby.css';
import '../../css/n/n01fo5_qx.css';
import '../../css/b/bjl-racht.css';
import '../../css/a/axtmyacbi.css';
import '../../css/e/esglpskpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ir4dw3bpl"/><path class="y2orggbby"/><path class="n01fo5_qx"/><path class="bjl-racht"/><path class="axtmyacbi"/><path class="esglpskpa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:gamepad-outline" /></template>
