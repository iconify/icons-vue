<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9x2wm1fy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="y9x2wm1fy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:apple" /></template>
