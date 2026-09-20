<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/s/sph30q-dz.css';
import '../../css/d/dx7iutb6u.css';
import '../../css/s/sh-bfimtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="sph30q-dz"/><path class="dx7iutb6u"/><path class="sh-bfimtx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:arrow-up" /></template>
