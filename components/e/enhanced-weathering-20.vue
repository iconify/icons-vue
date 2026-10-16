<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxsm3nbbt.css';
import '../../css/u/u0t0ofhbn.css';
import '../../css/e/e_v0ieb8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lxsm3nbbt"/><path class="u0t0ofhbn"/><path class="e_v0ieb8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:enhanced-weathering-20" /></template>
