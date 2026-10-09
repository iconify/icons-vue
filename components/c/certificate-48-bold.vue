<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shndm-bvf.css';
import '../../css/d/d7fixtb7r.css';
import '../../css/l/lghqnqgnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="shndm-bvf"/><path class="d7fixtb7r"/><path class="lghqnqgnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:certificate-48-bold" /></template>
