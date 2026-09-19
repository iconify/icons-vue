<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpqi2ybyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="fpqi2ybyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:bell-slash" /></template>
