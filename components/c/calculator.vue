<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq33_dvdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1023};
const content = `<path class="vq33_dvdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:calculator" /></template>
