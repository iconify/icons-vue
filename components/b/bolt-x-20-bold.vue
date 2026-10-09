<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilu3h65we.css';
import '../../css/a/aqsnv9bnd.css';
import '../../css/v/vox66xuav.css';
import '../../css/g/gdinynbrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ilu3h65we"/><path class="aqsnv9bnd"/><path class="vox66xuav"/><path class="gdinynbrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bolt-x-20-bold" /></template>
