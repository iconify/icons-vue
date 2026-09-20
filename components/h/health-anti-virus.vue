<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac3vaqbce.css';
import '../../css/r/rf8gf5fko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ac3vaqbce"/><path class="rf8gf5fko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:health-anti-virus" /></template>
