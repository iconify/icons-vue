<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zg4r-utgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zg4r-utgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:exclamation-thick" /></template>
