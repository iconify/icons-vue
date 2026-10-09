<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tztkndb_y.css';
import '../../css/u/ubixxqbpx.css';
import '../../css/x/xnnvlwb_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tztkndb_y"/><path class="ubixxqbpx"/><path class="xnnvlwb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cave-20" /></template>
