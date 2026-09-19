<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/s/syqbndbck.css';
import '../../css/z/zdzqnkbnl.css';
import '../../css/f/fr_tmn9fp.css';
import '../../css/x/xtsrmvj7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="syqbndbck"/><path class="zdzqnkbnl"/><circle class="fr_tmn9fp"/><circle class="xtsrmvj7o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:google-lens" /></template>
