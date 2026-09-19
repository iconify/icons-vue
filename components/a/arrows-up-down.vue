<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qb7k1eeah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="qb7k1eeah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:arrows-up-down" /></template>
