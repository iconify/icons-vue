<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnax8dbwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wnax8dbwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:checkmark-sharp" /></template>
