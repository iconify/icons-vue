<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nstk77byy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="nstk77byy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:kaggle" /></template>
