<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pivyf-bap.css';
import '../../css/e/eo4t4pbyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pivyf-bap"/><path class="eo4t4pbyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:magma-chamber-48-bold" /></template>
