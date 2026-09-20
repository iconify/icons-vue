<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjy7yupxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cjy7yupxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:backward-1" /></template>
