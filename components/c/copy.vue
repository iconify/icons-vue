<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp1re3c8g.css';
import '../../css/g/gdtbnxj2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fp1re3c8g"/><path class="gdtbnxj2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:copy" /></template>
