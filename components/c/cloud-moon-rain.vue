<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0m-ghb_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="l0m-ghb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:cloud-moon-rain" /></template>
