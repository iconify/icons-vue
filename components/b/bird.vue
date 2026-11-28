<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfv0oii_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfv0oii_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:bird" /></template>
