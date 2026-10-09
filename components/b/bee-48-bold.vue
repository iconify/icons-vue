<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plya-7jhm.css';
import '../../css/i/iurj758pl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="plya-7jhm"/><path class="iurj758pl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bee-48-bold" /></template>
