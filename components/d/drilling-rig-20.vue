<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbd13vizc.css';
import '../../css/i/imtkfjwmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jbd13vizc"/><path class="imtkfjwmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:drilling-rig-20" /></template>
