<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dix-bwb7j.css';
import '../../css/e/enqyk-b4p.css';
import '../../css/n/nq5_p_bzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dix-bwb7j"/><path class="enqyk-b4p"/><path class="nq5_p_bzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydro-plant-alert-20" /></template>
