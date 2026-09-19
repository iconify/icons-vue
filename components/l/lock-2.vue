<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0_p_sbcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g0_p_sbcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:lock-2" /></template>
