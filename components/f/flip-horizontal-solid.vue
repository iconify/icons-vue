<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uk6fksicr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="uk6fksicr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:flip-horizontal-solid" /></template>
