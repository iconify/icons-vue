<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/m/mm_wv7bbg.css';
import '../../css/h/hva14dy6h.css';
import '../../css/g/gga_tfa_r.css';
import '../../css/j/jo5ihnk1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="mm_wv7bbg"/><path class="hva14dy6h"/><rect class="gga_tfa_r"/><rect class="jo5ihnk1z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:in-as" /></template>
