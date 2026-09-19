<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dv46qlpec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="dv46qlpec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:cc-amazon-pay" /></template>
