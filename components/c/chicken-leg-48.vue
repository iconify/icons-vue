<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtz_8836t.css';
import '../../css/r/rd173ubeg.css';
import '../../css/f/ftbksp_ll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gtz_8836t"/><path class="rd173ubeg"/><path class="ftbksp_ll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chicken-leg-48" /></template>
