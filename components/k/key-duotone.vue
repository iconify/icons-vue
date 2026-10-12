<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/ukz87w37f.css';
import '../../css/c/c15q2jbtz.css';
import '../../css/h/hnmvecxnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ukz87w37f"/><path class="c15q2jbtz"/><path class="hnmvecxnc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:key-duotone" /></template>
