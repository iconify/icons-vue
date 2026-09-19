<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulw6jrbma.css';
import '../../css/j/jg-s2j-2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ulw6jrbma"/><path class="jg-s2j-2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:bitcoin-logo" /></template>
