<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4z2-gbtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="w4z2-gbtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:focus-points" /></template>
