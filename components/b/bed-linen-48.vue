<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fk2co3bdu.css';
import '../../css/p/ph74n2b1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fk2co3bdu"/><path class="ph74n2b1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bed-linen-48" /></template>
