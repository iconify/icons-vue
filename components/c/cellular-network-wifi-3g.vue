<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/z/zu-ux3bfk.css';
import '../../css/h/ht6_tfbrd.css';
import '../../css/r/rh4ip8yrd.css';
import '../../css/w/waw1v4lte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="zu-ux3bfk"/><path class="ht6_tfbrd"/><path class="rh4ip8yrd"/><path class="waw1v4lte"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:cellular-network-wifi-3g" /></template>
