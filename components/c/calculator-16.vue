<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sieez-brj.css';
import '../../css/v/v4lyffbho.css';
import '../../css/x/x7_vrbb-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="sieez-brj"/><path class="v4lyffbho"/><path clip-rule="evenodd" class="x7_vrbb-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:calculator-16" /></template>
