<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qmlj2lb5v.css';
import '../../css/g/gr4fk-o4v.css';
import '../../css/l/lhbek8bmf.css';
import '../../css/d/dfj0h6-ug.css';
import '../../css/w/w49j0rbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGKBLFQcQm"><g class="ft5dv1b6b"><path class="qmlj2lb5v"/><path class="gr4fk-o4v"/><path class="lhbek8bmf"/><path class="dfj0h6-ug"/></g></mask></defs><path mask="url(#SVGKBLFQcQm)" class="w49j0rbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:candlestick-duotone-line" /></template>
