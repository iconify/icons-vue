<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpeu_j1mo.css';
import '../../css/l/lyr6s0wuk.css';
import '../../css/b/by6gobvlv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tpeu_j1mo"/><path class="lyr6s0wuk"/><path class="by6gobvlv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:grant-48" /></template>
