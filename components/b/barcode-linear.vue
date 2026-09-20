<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/gl7x28b9l.css';
import '../../css/d/dclfiub7h.css';
import '../../css/y/y-d36rbtw.css';
import '../../css/e/e2jap3rke.css';
import '../../css/t/tgh9kpbtn.css';
import '../../css/j/j34g79pdg.css';
import '../../css/r/rcdscmf_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="gl7x28b9l"/><path class="dclfiub7h"/><path class="y-d36rbtw"/><path class="e2jap3rke"/><path class="tgh9kpbtn"/><rect class="j34g79pdg"/><rect class="rcdscmf_t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:barcode-linear" /></template>
