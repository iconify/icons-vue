<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aldytac9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="aldytac9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:credit-card" /></template>
