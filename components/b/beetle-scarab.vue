<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/l/lbdkbebfz.css';
import '../../css/l/lqm65lzzw.css';
import '../../css/b/btea2sv2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lbdkbebfz"/><path class="lqm65lzzw"/><path class="btea2sv2a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:beetle-scarab" /></template>
