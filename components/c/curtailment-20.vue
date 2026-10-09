<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xibxme48y.css';
import '../../css/p/pyo64viyh.css';
import '../../css/n/nk_swmbkl.css';
import '../../css/s/szxjw4bwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xibxme48y"/><path class="pyo64viyh"/><path class="nk_swmbkl"/><path class="szxjw4bwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:curtailment-20" /></template>
