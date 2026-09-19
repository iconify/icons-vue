<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rk7pu-57w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="rk7pu-57w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:hospital" /></template>
