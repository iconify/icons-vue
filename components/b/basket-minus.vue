<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idjh8_b1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idjh8_b1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:basket-minus" /></template>
