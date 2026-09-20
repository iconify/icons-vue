<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/qtn6etb4o.css';
import '../../css/h/ho3oitlqc.css';
import '../../css/k/ki0noac0g.css';
import '../../css/p/pb53-ibny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qtn6etb4o"/><path class="ho3oitlqc"/><path class="ki0noac0g"/><path class="pb53-ibny"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:image-upload" /></template>
