<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhjv-fbep.css';
import '../../css/h/hkvtvtm6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yhjv-fbep"/><path class="hkvtvtm6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:graduation-cap-48" /></template>
