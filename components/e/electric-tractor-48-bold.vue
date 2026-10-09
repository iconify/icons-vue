<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfao_6b1t.css';
import '../../css/c/c00kytlfm.css';
import '../../css/k/ka9ab8bek.css';
import '../../css/h/hss0ro0-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rfao_6b1t"/><path class="c00kytlfm"/><path class="ka9ab8bek"/><path class="hss0ro0-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:electric-tractor-48-bold" /></template>
