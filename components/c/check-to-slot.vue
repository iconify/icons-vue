<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/veq3ccc5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="veq3ccc5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:check-to-slot" /></template>
