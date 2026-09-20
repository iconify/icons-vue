<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inh5m1-1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="inh5m1-1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:fifa" /></template>
