<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tum2ujb2a.css';
import '../../css/t/tets5tbsv.css';
import '../../css/d/dmkkcgbra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="tum2ujb2a"/><path class="tets5tbsv"/><path class="dmkkcgbra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:jhipster-wordmark" /></template>
