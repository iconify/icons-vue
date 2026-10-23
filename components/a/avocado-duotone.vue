<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rya9mtv8n.css';
import '../../css/y/yt3a_1kmm.css';
import '../../css/v/veoxucbeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="rya9mtv8n"/><path class="yt3a_1kmm"/><path class="veoxucbeb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:avocado-duotone" /></template>
