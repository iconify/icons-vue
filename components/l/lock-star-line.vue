<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifl_fr9xs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifl_fr9xs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:lock-star-line" /></template>
