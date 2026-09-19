<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg-6srbit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="eg-6srbit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:clock-cycle-stroke-12" /></template>
