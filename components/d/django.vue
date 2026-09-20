<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lps2qmi-k.css';
import '../../css/h/hx8_3wb3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lps2qmi-k"/><path class="hx8_3wb3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:django" /></template>
