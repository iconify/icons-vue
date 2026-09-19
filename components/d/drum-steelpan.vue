<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgsxwe0_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="lgsxwe0_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:drum-steelpan" /></template>
