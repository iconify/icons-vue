<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opn24tbwg.css';
import '../../css/o/ov--w3k6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="opn24tbwg"/><path class="ov--w3k6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:energy-price-48-bold" /></template>
