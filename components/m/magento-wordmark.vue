<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9gx0vbsu.css';
import '../../css/k/kphlzacfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="q9gx0vbsu"/><path class="kphlzacfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:magento-wordmark" /></template>
