<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvn4mfbec.css';
import '../../css/l/lahmkil_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gvn4mfbec"/><path class="lahmkil_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:acorn-48" /></template>
