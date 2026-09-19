<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g549aub-r.css';
import '../../css/m/mipxudk3z.css';
import '../../css/g/gtrou0bvy.css';
import '../../css/y/y5ske3qnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><ellipse class="g549aub-r"/><path class="mipxudk3z"/><path class="gtrou0bvy"/><path class="y5ske3qnv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:database-backup" /></template>
