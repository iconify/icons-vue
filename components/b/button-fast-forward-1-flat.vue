<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rps_n-b1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rps_n-b1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:button-fast-forward-1-flat" /></template>
