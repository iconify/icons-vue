<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/sh8e0m06k.css';
import '../../css/o/oqzpqv97y.css';
import '../../css/x/xszjfht3t.css';
import '../../css/q/qu0eyjbrg.css';
import '../../css/m/my5268blj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="sh8e0m06k"/><path class="oqzpqv97y"/><path class="xszjfht3t"/><path class="qu0eyjbrg"/><path class="my5268blj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clipboard-linear" /></template>
