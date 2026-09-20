<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/n/nmlhygb4s.css';
import '../../css/g/gxnnybbyt.css';
import '../../css/s/sduaog7rg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nmlhygb4s"/><path class="gxnnybbyt"/><path class="sduaog7rg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bus-stop" /></template>
