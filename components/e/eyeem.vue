<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy-7v8bbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iy-7v8bbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:eyeem" /></template>
