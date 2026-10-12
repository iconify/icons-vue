<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mi97z4bps.css';
import '../../css/r/rh7ug_byb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mi97z4bps"/><path class="rh7ug_byb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:frog-48-bold" /></template>
