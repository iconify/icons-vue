<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aopgbcccu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="aopgbcccu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:battery-upright-full-check" /></template>
