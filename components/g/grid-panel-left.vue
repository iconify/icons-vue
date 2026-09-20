<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/p/py7iz3b4l.css';
import '../../css/y/y2ls4efbx.css';
import '../../css/t/td4pmbm2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><rect class="py7iz3b4l"/><rect class="y2ls4efbx"/><rect class="td4pmbm2c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:grid-panel-left" /></template>
