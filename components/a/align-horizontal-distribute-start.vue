<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/g/gcq9gub5a.css';
import '../../css/i/ioh4epz1v.css';
import '../../css/w/wyugrdu1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><rect class="gcq9gub5a"/><rect class="ioh4epz1v"/><path class="wyugrdu1u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:align-horizontal-distribute-start" /></template>
