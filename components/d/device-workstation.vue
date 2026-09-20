<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/h/hz3ugwbtm.css';
import '../../css/o/oqy67qbzl.css';
import '../../css/d/d54xwq8av.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hz3ugwbtm"/><path class="oqy67qbzl"/><path class="d54xwq8av"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-workstation" /></template>
