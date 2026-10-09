<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cr-pjp-tv.css';
import '../../css/l/lmp8iccnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cr-pjp-tv"/><path class="lmp8iccnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:corner-up-right-48" /></template>
