<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/n/nu43cebmy.css';
import '../../css/b/bf9hqaclw.css';
import '../../css/e/ec_xsy4gs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nu43cebmy"/><circle class="bf9hqaclw"/><circle class="ec_xsy4gs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:ambulance" /></template>
