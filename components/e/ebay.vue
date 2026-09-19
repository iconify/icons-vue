<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fodq4_j6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="fodq4_j6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:ebay" /></template>
