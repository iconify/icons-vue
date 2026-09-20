<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wc8otsboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="wc8otsboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:discount-percent-cutout-solid" /></template>
