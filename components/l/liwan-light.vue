<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyarh0b7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kyarh0b7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:liwan-light" /></template>
