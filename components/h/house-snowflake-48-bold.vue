<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxvnz_b5x.css';
import '../../css/n/njsy0lg8m.css';
import '../../css/i/ibk_3obac.css';
import '../../css/u/us_48ubxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uxvnz_b5x"/><path class="njsy0lg8m"/><path class="ibk_3obac"/><path class="us_48ubxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-snowflake-48-bold" /></template>
