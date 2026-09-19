<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftn1mcb_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ftn1mcb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:level-down" /></template>
