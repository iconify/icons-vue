<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asfiwqbnm.css';
import '../../css/l/l1y22fbdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="asfiwqbnm"/><path class="l1y22fbdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:gitkraken-wordmark" /></template>
