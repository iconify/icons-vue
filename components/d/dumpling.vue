<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf1wvbbac.css';
import '../../css/a/apfxgpb2j.css';
import '../../css/b/bbpzg73-s.css';
import '../../css/j/jpxo32bob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="pf1wvbbac"/><path class="apfxgpb2j"/><path paint-order="stroke fill markers" transform="matrix(.6322 .7748 -.7436 .6686 0 0)" class="bbpzg73-s"/><path class="jpxo32bob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:dumpling" /></template>
