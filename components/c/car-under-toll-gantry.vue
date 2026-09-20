<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dx8sbdbmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dx8sbdbmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:car-under-toll-gantry" /></template>
