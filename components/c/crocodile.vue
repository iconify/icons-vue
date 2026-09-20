<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae849gbxa.css';
import '../../css/s/skulppbui.css';
import '../../css/m/m16fbge1u.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/r/rqv1vgboq.css';
import '../../css/l/lpkqs1wkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<g class="ae849gbxa"><path class="skulppbui"/><path class="m16fbge1u"/></g><g class="ij2x_72vy"><path class="rqv1vgboq"/><path class="lpkqs1wkw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:crocodile" /></template>
