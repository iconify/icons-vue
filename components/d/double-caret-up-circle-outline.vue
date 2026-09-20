<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpm3sabez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lpm3sabez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:double-caret-up-circle-outline" /></template>
