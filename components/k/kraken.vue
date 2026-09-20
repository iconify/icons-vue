<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfzjyi6-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":32};
const content = `<path class="mfzjyi6-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:kraken" /></template>
