<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/lz14ttf8r.css';
import '../../css/o/oqzpqv97y.css';
import '../../css/x/xszjfht3t.css';
import '../../css/q/qu0eyjbrg.css';
import '../../css/m/m390b8qby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lz14ttf8r"/><path class="oqzpqv97y"/><path class="xszjfht3t"/><path class="qu0eyjbrg"/><path class="m390b8qby"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clipboard-linear" /></template>
