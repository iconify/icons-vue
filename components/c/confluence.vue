<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8xu67bmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x8xu67bmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:confluence" /></template>
