<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fklgh1ehi.css';
import '../../css/w/wszt4c0fp.css';
import '../../css/t/th5rvlnyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fklgh1ehi"/><circle class="wszt4c0fp"/><path class="th5rvlnyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-engineering-requirements-doors-next" /></template>
