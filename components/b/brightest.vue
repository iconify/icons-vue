<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsce67bmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nsce67bmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:brightest" /></template>
