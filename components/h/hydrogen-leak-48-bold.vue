<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dak927fpw.css';
import '../../css/g/gbl322bwz.css';
import '../../css/p/p8-zntblb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dak927fpw"/><path class="gbl322bwz"/><path class="p8-zntblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydrogen-leak-48-bold" /></template>
