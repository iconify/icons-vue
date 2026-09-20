<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pan_fhbhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="pan_fhbhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:error-multiple" /></template>
