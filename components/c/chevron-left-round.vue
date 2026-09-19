<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-pi-2n5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k-pi-2n5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:chevron-left-round" /></template>
