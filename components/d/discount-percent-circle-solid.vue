<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbwmmgipi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kbwmmgipi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:discount-percent-circle-solid" /></template>
