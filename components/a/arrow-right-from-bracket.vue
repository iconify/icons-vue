<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-_g9tire.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u-_g9tire"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:arrow-right-from-bracket" /></template>
