<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l-2_3be0a.css';
import '../../css/a/aljv-2bww.css';
import '../../css/p/pueowy_uh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="l-2_3be0a"/><path class="aljv-2bww"/><path clip-rule="evenodd" class="pueowy_uh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:fire-wall-flat" /></template>
