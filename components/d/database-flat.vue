<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/viv_y20jj.css';
import '../../css/b/bakwbrbca.css';
import '../../css/y/yen5i-bgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="viv_y20jj"/><path class="bakwbrbca"/><path clip-rule="evenodd" class="yen5i-bgb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:database-flat" /></template>
