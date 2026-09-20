<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr04byboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="nr04byboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:justify-left" /></template>
