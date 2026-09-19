<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdk43wh1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bdk43wh1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:logo-pinterest" /></template>
