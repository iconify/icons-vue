<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ri67s6byk.css';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/ce9ahpdno.css';
import '../../css/z/z391hm2yp.css';
import '../../css/d/dgpjfbb2z.css';
import '../../css/w/wuuk__4az.css';
import '../../css/g/g3rqoccuy.css';
import '../../css/k/kmlj0un-x.css';
import '../../css/m/mca-g9b_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1500,"height":1500};
const content = `<mask id="SVGKaOflcZt" width="1500" height="1500" x="0" y="0" mask-type="alpha" maskUnits="userSpaceOnUse"><path class="ri67s6byk"/></mask><g mask="url(#SVGKaOflcZt)" class="ft5dv1b6b"><path class="ce9ahpdno"/><path class="z391hm2yp"/><path class="dgpjfbb2z"/><circle class="wuuk__4az"/><circle class="g3rqoccuy"/><path class="kmlj0un-x"/><path clip-rule="evenodd" class="mca-g9b_h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:emissary-ingress-light" /></template>
