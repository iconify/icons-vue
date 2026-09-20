<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f_pv1tbov.css';
import '../../css/s/sdsnqtvsn.css';
import '../../css/c/che3vpvsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f_pv1tbov"/><path class="sdsnqtvsn"/><path class="che3vpvsq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:lamp-light" /></template>
