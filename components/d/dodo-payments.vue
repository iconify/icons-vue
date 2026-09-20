<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2fn2abzx.css';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/v3j0k_b4s.css';
import '../../css/i/icmaxyehs.css';
import '../../css/b/b51eov4tp.css';
import '../../css/a/a46liac2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":121,"height":121};
const content = `<mask id="SVGGFUgfdJB" width="91" height="76" x="18" y="27" maskUnits="userSpaceOnUse" style="mask-type:luminance"><path class="o2fn2abzx"/></mask><g class="ft5dv1b6b"><path class="v3j0k_b4s"/><g mask="url(#SVGGFUgfdJB)" class="icmaxyehs"><path class="b51eov4tp"/><path class="a46liac2f"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:dodo-payments" /></template>
