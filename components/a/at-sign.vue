<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kio30xvjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="kio30xvjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:at-sign" /></template>
