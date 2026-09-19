<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uab_dab1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uab_dab1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:bread-slice" /></template>
