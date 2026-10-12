<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tn-gj8b2k.css';
import '../../css/e/e6okdcehl.css';
import '../../css/z/zplvpsp2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tn-gj8b2k"/><path class="e6okdcehl"/><path class="zplvpsp2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:images-48" /></template>
