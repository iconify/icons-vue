<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/acs7iwixh.css';
import '../../css/n/n8sfv5b_b.css';
import '../../css/w/w49j0rbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGNvrGqb2w"><g class="ft5dv1b6b"><path class="acs7iwixh"/><path class="n8sfv5b_b"/></g></mask></defs><path mask="url(#SVGNvrGqb2w)" class="w49j0rbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:bell-duotone-line" /></template>
