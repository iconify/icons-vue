<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ri67s6byk.css';
import '../../css/n/n1mjunbsu.css';
import '../../css/e/enn5_5gkx.css';
import '../../css/a/a59nmvo8r.css';
import '../../css/c/cd_azfjbw.css';
import '../../css/t/t3fvyhq0h.css';
import '../../css/m/md_fwibdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1500,"height":1500};
const content = `<mask id="SVGKaOflcZt" width="1500" height="1500" x="0" y="0" mask-type="alpha" maskUnits="userSpaceOnUse"><path class="ri67s6byk"/></mask><g mask="url(#SVGKaOflcZt)" class="n1mjunbsu"><path clip-rule="evenodd" class="enn5_5gkx"/><circle class="a59nmvo8r"/><circle class="cd_azfjbw"/><path class="t3fvyhq0h"/><path clip-rule="evenodd" class="md_fwibdh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:emissary-ingress-dark" /></template>
