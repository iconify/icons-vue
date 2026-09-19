<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/he1q6_b1l.css';
import '../../css/v/vzzpw72td.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="he1q6_b1l"/><path class="vzzpw72td"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:hugo-wordmark" /></template>
