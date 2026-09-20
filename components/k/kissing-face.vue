<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/az7hstbmu.css';
import '../../css/u/u5g-e0pir.css';
import '../../css/t/tdhzq11dq.css';
import '../../css/k/k4z7zsbhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="az7hstbmu"/><path class="u5g-e0pir"/><path class="tdhzq11dq"/><circle class="k4z7zsbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:kissing-face" /></template>
