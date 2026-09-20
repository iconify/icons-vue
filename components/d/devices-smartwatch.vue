<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nulrnh3xl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nulrnh3xl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:devices-smartwatch" /></template>
