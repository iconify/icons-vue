<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/w/w22_v0jqn.css';
import '../../css/l/lg_sgwbbl.css';
import '../../css/y/ym253vn8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="w22_v0jqn"/><path class="lg_sgwbbl"/><path class="ym253vn8u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:database" /></template>
