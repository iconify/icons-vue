<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smusfyo3e.css';
import '../../css/g/gc1ce0bgt.css';
import '../../css/o/oexyxwbsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="smusfyo3e"/><path class="gc1ce0bgt"/><path class="oexyxwbsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ballot-box-20" /></template>
