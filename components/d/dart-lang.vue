<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muoe_lbgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="muoe_lbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:dart-lang" /></template>
