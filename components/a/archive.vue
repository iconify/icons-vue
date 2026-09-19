<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2aa4fbfg.css';
import '../../css/r/r-selsbww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v2aa4fbfg"/><path class="r-selsbww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:archive" /></template>
