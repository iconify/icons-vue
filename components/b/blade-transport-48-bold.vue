<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bu9o71bva.css';
import '../../css/r/rudk7ubrf.css';
import '../../css/u/u2axsqyum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bu9o71bva"/><path class="rudk7ubrf"/><path class="u2axsqyum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:blade-transport-48-bold" /></template>
