<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qklghdczf.css';
import '../../css/o/olpeleb8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qklghdczf"/><path class="olpeleb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:acorn-20" /></template>
