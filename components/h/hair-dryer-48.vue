<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyjx8ab4r.css';
import '../../css/e/e2y089rqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cyjx8ab4r"/><path class="e2y089rqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hair-dryer-48" /></template>
