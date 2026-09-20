<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/v/vmfu1uq8n.css';
import '../../css/d/dy7pw87lu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vmfu1uq8n"/><circle transform="rotate(45 14.828 9.172)" class="dy7pw87lu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:comet" /></template>
