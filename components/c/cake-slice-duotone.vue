<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pz_aubc6p.css';
import '../../css/v/vra2vcckp.css';
import '../../css/p/pc1i8hn5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pz_aubc6p"/><path class="vra2vcckp"/><path class="pc1i8hn5i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cake-slice-duotone" /></template>
