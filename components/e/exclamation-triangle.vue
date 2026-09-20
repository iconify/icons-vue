<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tiu4lcw5h.css';
import '../../css/e/e0la5wsre.css';
import '../../css/r/rz3ur5bsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tiu4lcw5h"/><path class="e0la5wsre"/><ellipse class="rz3ur5bsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:exclamation-triangle" /></template>
