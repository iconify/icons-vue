<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t662f0tno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="t662f0tno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:credit-card" /></template>
