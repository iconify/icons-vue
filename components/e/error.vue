<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fys9o6byi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fys9o6byi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:error" /></template>
