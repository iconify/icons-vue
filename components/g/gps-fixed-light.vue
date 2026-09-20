<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/f/f_362pbxn.css';
import '../../css/n/n1xy6nh9u.css';
import '../../css/f/f8_k5bc_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><circle class="f_362pbxn"/><circle class="n1xy6nh9u"/><path class="f8_k5bc_f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:gps-fixed-light" /></template>
