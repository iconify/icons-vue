<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ej37iwbrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ej37iwbrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:book" /></template>
