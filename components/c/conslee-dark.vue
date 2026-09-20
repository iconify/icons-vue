<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eau1cd7mu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eau1cd7mu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:conslee-dark" /></template>
