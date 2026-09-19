<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nu9x3g38j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="nu9x3g38j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:apacheairflow-wordmark" /></template>
