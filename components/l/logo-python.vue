<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sf7q6ji8c.css';
import '../../css/f/fvnxa3bsu.css';
import '../../css/m/mi_58-bbi.css';
import '../../css/l/leai81bxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sf7q6ji8c"/><path class="fvnxa3bsu"/><path class="mi_58-bbi"/><path class="leai81bxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:logo-python" /></template>
