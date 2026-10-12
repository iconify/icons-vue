<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/ftp10o2ba.css';
import '../../css/n/nkre2v4-p.css';
import '../../css/y/yy397xbou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ftp10o2ba"/><path class="nkre2v4-p"/><path class="yy397xbou"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cone-duotone" /></template>
