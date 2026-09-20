<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/a5_xztpbo.css';
import '../../css/f/f9bz07hha.css';
import '../../css/l/l408b8b8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><rect class="a5_xztpbo"/><rect class="f9bz07hha"/><path clip-rule="evenodd" class="l408b8b8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:battery-full-light" /></template>
