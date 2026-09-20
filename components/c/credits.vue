<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/u/usve24bks.css';
import '../../css/l/l0bbvr7zu.css';
import '../../css/t/t3oiopagy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="usve24bks"/><path class="l0bbvr7zu"/><path class="t3oiopagy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:credits" /></template>
