<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/so9b0vatz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":446,"height":512};
const content = `<path class="so9b0vatz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:korvue" /></template>
