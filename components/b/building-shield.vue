<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0ndhbc1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="i0ndhbc1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:building-shield" /></template>
