<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/m/mmta-hb1g.css';
import '../../css/s/shu3xdl9q.css';
import '../../css/i/idbbthb2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mmta-hb1g"/><circle class="shu3xdl9q"/><circle class="idbbthb2f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:circle-person-arms-spread" /></template>
