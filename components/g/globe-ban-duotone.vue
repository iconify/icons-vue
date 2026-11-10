<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vp54agb5c.css';
import '../../css/i/im-u2lvxf.css';
import '../../css/k/ktki8hgxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vp54agb5c"/><path class="im-u2lvxf"/><path class="ktki8hgxj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:globe-ban-duotone" /></template>
