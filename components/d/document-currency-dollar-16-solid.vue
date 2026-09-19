<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7_-kbcvl.css';
import '../../css/d/dqlj_tyvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h7_-kbcvl"/><path clip-rule="evenodd" class="dqlj_tyvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:document-currency-dollar-16-solid" /></template>
