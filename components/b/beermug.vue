<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md5rxcbgi.css';
import '../../css/r/rh_lsv0bg.css';
import '../../css/q/qhf2oqbcs.css';
import '../../css/m/mmdfc-b9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="md5rxcbgi"/><path class="rh_lsv0bg"/><path class="qhf2oqbcs"/><path class="mmdfc-b9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:beermug" /></template>
