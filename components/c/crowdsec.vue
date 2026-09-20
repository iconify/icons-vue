<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpqstnbkt.css';
import '../../css/j/jobm0_deg.css';
import '../../css/u/um_60vbsp.css';
import '../../css/k/k8kt187zo.css';
import '../../css/w/wyu3oubvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rpqstnbkt"/><path class="jobm0_deg"/><path class="um_60vbsp"/><path class="k8kt187zo"/><path class="wyu3oubvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:crowdsec" /></template>
