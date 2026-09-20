<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvp-jbc3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="wvp-jbc3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:building-block" /></template>
