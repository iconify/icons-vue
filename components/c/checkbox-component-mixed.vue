<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctgsm2yze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ctgsm2yze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:checkbox-component-mixed" /></template>
