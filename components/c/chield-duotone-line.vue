<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivjvz2eii.css';
import '../../css/t/tcdfmzher.css';
import '../../css/a/almsit-4x.css';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/ese8babqc.css';
import '../../css/i/ipdr_abfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGrX5MMegh" width="18" height="20" x="3" y="1" maskUnits="userSpaceOnUse" class="ivjvz2eii"><path class="tcdfmzher"/><path class="almsit-4x"/></mask><g class="ft5dv1b6b"><path class="ese8babqc"/><path mask="url(#SVGrX5MMegh)" class="ipdr_abfn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:chield-duotone-line" /></template>
