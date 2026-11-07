<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhw3f2lhi.css';
import '../../css/h/halx4mbsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uhw3f2lhi"/><path class="halx4mbsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:key-minimalistic-2-bold-duotone" /></template>
