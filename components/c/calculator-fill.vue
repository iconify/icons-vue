<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmbk-01jh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmbk-01jh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:calculator-fill" /></template>
